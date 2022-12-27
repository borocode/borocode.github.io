---
title: "Okay Time for an Update"
date: 2022-08-15T20:24:02-04:00
draft: true
---

Didn't get too much done on this yesterday but got the Arch install working on the $40 1tb NVMe I picked up on Facebook Marketplace. The seller mentioned it was their main drive for three years... naturally, I wrote the drive off as faulty when a fresh Arch install would just crash randomly. 

Not sure if it was a soft lock but my mouse could move but I could not complete anything in the OS. Networking was still working but my Firefox would stop responding. Could not do anything in Konsole.

The Arch build is a 2700x on a ASUS X370-F GAMING with a 3080. I use this same machine 24/7 with HiveOS (16gb SATA SSD) so I know it is a working machine. 

How I fixed it? Not sure exactly but was up til morning with no issues before booting back into HiveOS with confidence (more on that lil later). I used pamac to install disable-c6-systemd, enabled IOMMU and changed power idle control to typical current in the motherboards BIOS and disabled APST by adding this kernel parameter nvme_core.default_ps_max_latency_us=0 to GRUB (I hope I am explaining this sufficiently). 

Referencing the Arch Linux wiki namely Ryzen and NVMe pages and a few other bug reports I found while Googling. 

So while Arch works great (so far), I wish I got the same hashrate I get on HiveOS (86 mh/s on Arch 515.xx, 92+ mh/s on HiveOS 455.xx) but maybe with some more tweaking I can get it closer. Currently, just finished my 3x5 for the day and added a stats page to the menu (hamburger with "About" page) with a working table. 

To accomplish this, I am exporting .csv from PERSEUS iOS app, using Tailscale to send it to myself via home Synapse/Matrix server on Element messenger and am using https://www.tablesgenerator.com/markdown_tables so I can easily display the table on Hugo. Kind of a clunky flow but if I make updates only once or twice a week it should be something I can handle. 

I have all my boxes out of both of the storage rooms because I was looking for the NVMe heatsink I got with my main rigs Sabrent RMA drive. I found the heatsink yesterday (was in a box under some boxes in a room) but I just ate for the first time today (ramen, "Shin Black with beef bone broth" and before microwave garnished with small bits of beef jerky, still hungry but will figure it out) so I am just typing this procrastinating (and in pain, lowkey) instead of putting boxes back on boxes in a room. 

Okay. 

Time to type "draft: false", save the file, stage changes, commit changes and push/sync. 

Wait. I didn't even proof read the last paragraph. Oops. Let's try this again.