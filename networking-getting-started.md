##Where to Start
I honestly think the best place to start would be to buy a new router/switch/firewall combo, install DD-WRT on it and place it between yourself and the internet. There are loads of free resources, but if you're like me, unless it's really important, you'll put it off. I'm incredibly talented when it comes to purchasing ebooks and training videos, but not always that great at reading and watching them. Once you have an unconfigured device, I'm sure you can think of a powerful motivator that will force you to learn how to set it up properly before you get any access going. Things like: Netflix, Gmail, Twitter, heck maybe even something like Grindr :)

To that end, I'm going to list a few things that I've done in the past that helped me, but expect to get suggestions as to other ways of aquiring cheap or free hardware to get you going. 

- If your ISP has given you a device to use on their network, this isn't what you'll want to work with, even if you can. 
- Just because something has a long feature list and supports IEEE 802.11super doesn't mean you'll need to pay $200 USD and up for it... let's keep it simple! 
- Whatever operating system you run probably has some sort of networking. Plan-9, AIX, Commodore64, you're good to go. Many of the tools listed below might be OS-specific, but there are almost always alternatives or tools that provide the same functionality. That being said, I will focus primarily on Linux, then MacOS, then Windows in that order. Unless mentioned, assume the tool is for Linux.  

##Cheap Device
Don't overthink it - get something cheap and easy, you can always upgrade later. 
D-Link DIR-300 - this can be had at a local Staples for about $28 last I checked. If not, have a look at the [DD-WRT list or supported devices](http://www.dd-wrt.com/wiki/index.php/Supported_Devices#D-Link) and find one you can source locally for about $30 

##Build Your Own
There's always the option of building your own router using an old computer and a supported wireless adapter. I won't cover all of the options here, but often an old laptop with a wireless USB dongle is enough. I'd suggest Ubuntu as a start, but if you're feeling adventurous, a server running [Vyatta (can be a VM)](http://vyos.net/wiki/Main_Page), [Sophos UTM (Previously Astaro, can be VM)](https://www.sophos.com/en-us/products/free-tools/sophos-utm-home-edition.aspx) or [ClearOS (can be a VM)](http://www.clearfoundation.com/#clearfoundation-community). There's also a [monster list of router/firewall distros on Wikipedia](https://en.wikipedia.org/wiki/List_of_router_and_firewall_distributions) if you want to do some research. 

##Eumlate/Simulate It
Sometimes it's difficult to do things like simulate (really emulation, but we'll leave the misnomer in place) packet loss and latency with one device. Luckily you can set up a router sim to make very complex networks quite easily. In the past I've used [GNS3](http://www.gns3.com/) for this task, but recently [CORE (from the US Navy, no less)](http://www.nrl.navy.mil/itd/ncs/products/core) and [IMUNES](http://imunes.net/) have made it onto the radar as well.

##A Quick Note On Cabling
If you end up in a datacenter, dealing with physical cables, you'll want to learn about cabling - It will make people who deal with your work later much more likely in either hiring you again or not blaming you for all manner of issues that might not even be related. To that end, APC (Schneider Electric) set up some free courses online that cover cabling. You'll need to register, but the deep link to the [free datacenter cabling course is here](http://energy.schneideruniversities.com/student.php?ctg=lessons&catalog=1&info_course=85).
