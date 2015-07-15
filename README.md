# PEH-wifi-attack v0.6.0 
Framework for PEH-wifi-attack
![Tool Home](https://www.dropbox.com/s/rdj1skbfbiim11k/logo.jpg?dl=0)
---
### dependencies:
* Python-scapy
* Python-nmap
* BeautifulSoup
* Airbase-ng include in aircrack-ng
* DHCP-server

#### Ubuntu and Kali install
```sh
$ chmod +x install.sh
```
```sh
$ sudo ./install --install
```
#### [install DHCP in  Debian-based]

##### Ubuntu

```sh
$ sudo apt-get install isc-dhcp-server
```

##### Kali linux

```sh
$ echo "deb http://ftp.de.debian.org/debian wheezy main " >> /etc/apt/sources.list
$ apt-get update && apt-get install isc-dhcp-server
```

#### [install DHCP in  redhat-based]

##### Fedora

```sh
$ sudo yum install dhcp
```

### Tools
-  Etter.dns: Edit etter.dns to loading module dns spoof.

-  Dns Spoof: Start dns spoof attack in interface ath0 fake AP.

- Ettercap: Start ettercap attack in host connected AP fake Capturing login credentials.

-  Sslstrip: The sslstrip listen the traffic on port 10000.

-  Driftnet: The driftnet sniffs and decodes any JPEG TCP sessions, then displays in  an window.


### Modules
* Deauth Attack: kill all devices connected in AP (wireless network) or the attacker can Also put the Mac-address in the Client field, Then only one client disconnects the access point.

* Probe Request:  Probe request  capture the  clients trying to connect to AP,Probe requests can be sent by anyone with a legitimate Media Access Control (MAC) address, as association to the network is not required at this stage.

* Mac Changer: you can now easily spoof the MAC address. With a few clicks, users will be able to change their MAC addresses.

* Device FingerPrint:  list devices connected the network mini fingerprint, is information collected about a local computing device.

* DHCP Starvation Attack: this module DHCP Starvation can be classified as a Denial of Service attack. is an attack that works by broadcasting vast numbers of DHCP requests with spoofed MAC addresses simultaneously.

* DNS Spoof Manager: this module DNS spoofing is the making change in hostname ip-address table, this table tells the route will be that DNS address for that particular IP address, thus changing the address of this table we can redirect wherever we want.

* Windows Update Attack:  this module is an attack DNS spoof que generate an update the page fake Windows, causing the victim to download a fake file update. 

* ARP Posion Attack:  change tables ARPspoof the target and redirect all request tcp to ip attacker.
## Videos tutorials:
[Demo 1](http://www.youtube.com/watch?v=Jrb43KVPIJw)
--
[Demo 2](http://youtu.be/qVGLGNYyLzg)
--
[Demo 3](http://youtu.be/rNWvpV6NZoI)
--
The MIT License (MIT)

Copyright (c) 2015 P0cL4bs Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
