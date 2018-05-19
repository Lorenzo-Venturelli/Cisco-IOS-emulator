# Virtual machine based on Debian x64 with emulation of Cisco 7200 Router.
It has 2 users:
**root**, with administrative privileges on the Debian machine
**studente**, configured to automatically start the emulation of the Cisco router.
The password for anything is **fermi**.
### Important!
To ensure that the emulation works properly, you must run the machine with the network interface in Bridge mode on an Ethernet Host interface.
Wireless Host interfaces do not allow the Router to function properly outside the VirtualBox VLAN.
