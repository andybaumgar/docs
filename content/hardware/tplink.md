---
layout: page
title: "TP-Link Indoor Router"
category: Hardware
---

An indoor router, connected by ethernet cable to the outdoor router, is required for an NYC Mesh member to connect their personal devices to the Internet. For volunteer-led installations, the install team will supply the new member with a [TP-Link Archer A6](https://www.tp-link.com/us/home-networking/wifi-router/archer-a6/) or a [TP-Link Archer A7](https://www.tp-link.com/us/home-networking/wifi-router/archer-a7/).

![alt text](https://i.imgur.com/d1S8Q60.png "TP-Link Router")


### Pre-Configuration Best Practices
**For volunteer installers**

Before configuring, ask the user member to tell you:

* Whether they would like to use the TP-Link router we supply or their own router
* A username and password for the router
* An SSID and password for the home wireless network

### TP-Link Archer A6 or A7 Router Configuration Instructions
**For volunteer installers and DIY installers**

![alt text](https://i.imgur.com/oq6yWHZ.png "TP-Link Router")

1.  Plug the ethernet cable from the outdoor antenna/router into the TP-Link’s blue WAN port.
1.  Plug the power adapter into the wall and the cable into the power socket of the router. The router will turn on automatically.
1.  Connect the installation laptop to the router by plugging an Ethernet patch cable into the yellow LAN port or via Wifi (see the underside of the router for SSID and pwd)

1.  Navigate to the router dashboard in an Internet browser. The Default IP address is **192.168.0.1**
    *  Username: **admin** (or whatever it says on the underside of the router)
    *  Password: **admin** (or whatever is says on the underside of the router)

1.  Set up the guest WiFi to “**-NYC Mesh guest-**” (including the dashes).
Navigate to “Guest Network” and set as follows: ![alt text](https://i.imgur.com/BXzdita.jpg "Guest Network Configuration Settings")

1.  Set up the home WiFi.
Navigate to Wireless > Basic Settings
to set the home WiFi network SSID you wish to use and  navigate to Wireless > Wireless Security to set the password.

1.  Replace the router’s admin/admin login with a more secure username and password.
Navigate to System Tools > Password and input a new username and password.

1. Please read [Obligations](https://www.nycmesh.net/faq#obligations)


### Optional TP-Link TL-WR841N Firmware Upgrade
**For volunteer installers**

If you have time you should pre-configure the router as much as possible, including upgrading the firmware to the latest version. To do that the router does not need to be connected to a network. It can be pre-configured following the above steps excluding point 1.

1.  Download the latest firmware file [here for the A6](https://www.tp-link.com/us/support/download/archer-a6/#Firmware)or [here for the A7](https://www.tp-link.com/us/support/download/archer-a7/#Firmware).
1.  Connect to **192.168.0.1** and log in with the username and password you set for the router.
1.  Go to System Tools > Firmware Upgrade.
1.  Click Choose File to locate the downloaded firmware file, and click Upgrade.
1.  Setting the time is not a necessity but nice to do. Go to System Tools > Time Settings. You can use [apple NTP](http://time.apple.com), [pool.org](http://pool.ntp.org) and/or [Google](http://time1.google.com).


### Support
**For volunteer installers and DIY installers**

A Quick Installation Guide and User Guide can be downloaded [here for the Archer A6](https://www.tp-link.com/us/support/download/archer-a6/) and [here for the Archer A7](https://www.tp-link.com/us/support/download/archer-a7/).
