# cidr2ip
Little script to convert CIDR notation to distinct IP addresses.

## About
As the original respository for this script has vanished, and with the licence permitting it, I'm republishing this Perl script.

* Original Author : [Steve Kemp](https://steve.fi/)
* Licence : As mentioned in the script, it uses the same as Perl (GPLv1 if I follow the Perl 5.24 README correctly). Interestingly, the script contain both a Copyright Notice AND the Free Software notification.

## Usage
It's as simple as calling the script with the CIDR range as parameter :
```sh
[seboss666@seboss666-pc ~ ]$ cidr2ip 192.168.1.0/24
192.168.1.0
192.168.1.1
192.168.1.2
192.168.1.3
192.168.1.4
192.168.1.5
(...)
```

## Installation
Just download the script or clone this repository, and be sure to have it somewhere in your `PATH` environment variable. Oviously, you need Perl installed.

## Known Limitations
It's only usable for IPv4 addresses. You also has to use a shell pipe and grep/less/whatever to search through results.

