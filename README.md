Dynamic ARP Inspection (DAI) is a security feature that protects ARP (Address Resolution Protocol) which is vulnerable to an attack like ARP poisoning.

DAI checks all ARP packets on untrusted interfaces, it will compare the information in the ARP packet with the DHCP snooping database and/or an ARP access-list. If the information in the ARP packet doesn’t matter, it will be dropped






NOTE: IT IS REQUIRED TO CONFIGURE DHCP SNOOPING FIRST!


CREDIT: networklessons.com
