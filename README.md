# scanip

IP and Mac address scanner

## try

Arch Linux:

``` console
$ sudo pacman -S tcpdump
$ sudo pip2 install scapy
$ git clone https://github.com/alexandre-mbm/scanip.git
$ cd scanip
$ sudo python2
Python 2.7.13 (default, Dec 21 2016, 07:16:46) 
[GCC 6.2.1 20160830] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> import scanip
>>> scanip.start_scan()
Begin emission:
.**Finished to send 256 packets.
***..................................
Received 40 packets, got 5 answers, remaining 251 packets
xx:xx:xx:xx:xx:xx <---------> 192.168.0.1
xx:xx:xx:xx:xx:xx <---------> 192.168.0.34
xx:xx:xx:xx:xx:xx <---------> 192.168.0.12
xx:xx:xx:xx:xx:xx <---------> 192.168.0.11
xx:xx:xx:xx:xx:xx <---------> 192.168.0.14
>>> 

```
