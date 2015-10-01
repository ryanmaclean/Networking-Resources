# Networking-Resources
Resources for those beginning networking. Made for the DevOps crowd but (hopefully) should really be useful for anyone.

##Where to Start
I honestly think the best place to start would be to buy a new router/switch/firewall combo, install DD-WRT on it and place it between yourself and the internet. I'm sure you can think of a powerful motivator that will force you to learn how to set it up properly before you get any access going. Things like: Netflix, Gmail, Twitter, heck maybe even something like Grindr :)

To that end, I'm going to list a few things that I've done in the past that helped me, but expect to get suggestions as to other ways of aquiring cheap or free hardware to get you going. 

1) If your ISP has given you a device to use on their network, this isn't what you'll want to work with, even if you can. 
2) Second: just because something has a long feature list and supports IEEE 802.11super doesn't mean you'll need to pay $200 USD and up for it... let's keep it simple! 
3) Whatever operating system you run probably has some sort of networking. Plan-9, AIX, Commodore64, you're good to go. Many of the tools listed below might be OS-specific, but there are almost always alternatives or tools that provide the same functionality. That being said, I will focus primarily on Linux, then MacOS, then Windows in that order. Unless mentioned, assume the tool is for Linux.  

##Cheap Device
D-Link DIR-300 - this can be had at a local Staples for about $28 last I checked. If not, have a look at the [DD-WRT list or supported devices](http://www.dd-wrt.com/wiki/index.php/Supported_Devices#D-Link) and find one you can source local for about $30 

##Build Your Own
There's always the option of building your own router using an old computer and a supported wireless adapter. I won't cover all of the options here, but often an old laptop with a wireless USB dongle is enough. I'd suggest Ubuntu as a start, but if you're feeling adventurous, a server running [Vyatta (can be a VM)](http://vyos.net/wiki/Main_Page), [Sophos UTM (Previously Astaro, can be VM)](https://www.sophos.com/en-us/products/free-tools/sophos-utm-home-edition.aspx) or [ClearOS (can be a VM)](http://www.clearfoundation.com/#clearfoundation-community). 

##Tools
- iptraf - Command Line IP Traffic Monitor - [IPTraf User's Guide](http://iptraf.seul.org/2.7/manual.html)
- [ntopng - Web-based Traffic Monitoring](https://github.com/ntop/ntopng)
- [smokeping](https://oss.oetiker.ch/smokeping/index.en.html) - Web-based ping checker - [Ubuntu Install Guide (Sparse)](http://manpages.ubuntu.com/manpages/trusty/man7/smokeping_install.7.html)
- mtr - My TraceRoute, Console Alternative to Pingplot [Diagnosing Issues with MTR](https://www.linode.com/docs/networking/diagnostics/diagnosing-network-issues-with-mtr)
- rancid - Open Source Network Configuration Management [Howto: Network Backups with RANCID](http://www.linuxhomenetworking.com/wiki/index.php/Quick_HOWTO_:_Ch1_:_Network_Backups_With_Rancid)
- screen - Useful for Serial Connections as Well!
- wireshark - [User Guide](https://www.wireshark.org/docs/wsug_html_chunked/)
- tcpdump - [SANS Institute TCP Dump Primer](https://www.giac.org/paper/gsec/3489/beginners-guide-tcpdump/105700)
- nmap - [Nmap from Beginner to Advanced (InfoSec)](http://resources.infosecinstitute.com/nmap/)
- nc/Netcat [Guide to Netcat from Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-use-netcat-to-establish-and-test-tcp-and-udp-connections-on-a-vps), [Netcat cheet sheet](https://www.sans.org/security-resources/sec560/netcat_cheat_sheet_v1.pdf)
- [Multiping / PingPlotter (OSX/iOS/Windows, not free)](https://www.pingman.com/products.html)
- sipcalc (subnet calc) - [Ubuntu Sipcalc Manpage](http://manpages.ubuntu.com/manpages/hardy/man1/sipcalc.1.html)
- DiG DNS Tool [Beginner's Guide](https://www.madboa.com/geek/dig/)
- [GNS3 Network Sim](http://www.gns3.com/)
- [The Dude Network Mapper (Windows-only, free)](http://www.mikrotik.com/thedude)

##Online Tools
- [DNS Stuff](http://www.dnsstuff.com/)
- [MX Toolbox](http://mxtoolbox.com/)
- [DNS Propagation Checker](https://www.whatsmydns.net/)

##Forums
- [Arstechnica Networking](http://arstechnica.com/civis/viewforum.php?f=10&sid=23fb503736d39115efd931df2b863175)
 

##Knowledge Bases
- [Cisco](http://www.cisco.com/cisco/web/psa/reference.html)
- [Juniper](https://kb.juniper.net/InfoCenter/index?page=home)
- [Riverbed](https://supportkb.riverbed.com/support/index?page=home)

##Free Training
- [MS Networking Essentials](https://www.microsoftvirtualacademy.com/en-us/training-courses/networking-fundamentals-8249?l=zcmNgKKy_1704984382)
- [Juniper Training](https://learningportal.juniper.net/juniper/user_courses.aspx)
- [Linux Netowkring Howto](http://www.tldp.org/HOWTO/NET3-4-HOWTO.html)
- [Gentoo Networking Guide (replace emerge with your package manager :)](http://www.tldp.org/HOWTO/NET3-4-HOWTO.html)

##Config Management
- [Chef Cisco Cookbook for NXOS](https://supermarket.chef.io/cookbooks/cisco-cookbook)
- [JPupper for Junos/Puppet](https://downloads.puppetlabs.com/junos/2.0R1.1/)
- [rConfig Open Source Netowrk Config Management](http://www.rconfig.com/)
- [Arch Wiki Working with the Serial Console](https://wiki.archlinux.org/index.php/Working_with_the_serial_console)
