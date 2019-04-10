---
layout: archive
title: "My personal server"
permalink: /server/
author_profile: true
---

{% include base_path %}

I recently built my own low-power home server, which runs on ArchLinux (my favourite distribution) and provides cloud storage and streaming services for my family.
The server houses a low power mini-ITX motherboard with a soldered Intel Apollo Lake J3455 4-core CPU.
It has room for 4 standard 3.5" hard drives; currently it runs two 3TB data disks and one 1TB drive for OS backups and caches.
The OS is hosted on a 500GB SSD.

Notable software:

- Netdata for system monitoring;
- QBittorrent for torrenting;
- NextCloud for data sharing in the cloud;
- Plex for video and music streaming;
- NFS and SFTP for remote access to data;
- BTRFS for data mirroring and protection;
- A Steam cache is currently my next upcoming improvement.

The server sits in our bedroom, so the challenge was to make it almost completely silent: this was accomplished by building a small wooden, noise-absorbing case around one large 20cm Noctua fan whose speed is controlled by the temperature of the hard drives. Most of the time the fan is off and the system uses natural convection for cooling, thanks to the large opening in the top.

Power usage is 12W at idle and around 40-50W at peak usage (usually when scrubbing the drives).
