# Timeline
## 08.03.2026
- installed Virtualbox
- successfully pinged from cmd using ping 192.168.56.1 that shows the virtual cable is plugged in and working, the virtual network card is active and linked and windows host has a valid ip address on the virtual subnet.
- layer 1 and layer 2 the virtual network card is active and linked
- layer 3 as it got a valid IP Address
- **Metasploitable2** 
    - download
    - created a new VM where I assigned the extracted 'metasploitable.vmdk' as a virtual hard disk
    - changed the network adapter to the *VirtualBox Host-Only Ethernet*
    - powered it up
    - ran the first command *ip addr show eth0* that verified layer 3 (Network Layer)
    - returned the IP Address *192.168.56.102*


