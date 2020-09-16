## Dynamic routing protocols

When using the RIP protocol (a dynamic routing protocol) the convergence time might be extremely long (even 5 minutes or longer) in the case of a sudden change in the network topology. In our tests, this has happened in a virtual network of 3 emulated routers. We have not tested different configurations so this problem might not always occur.

The problems described above did not occur with the use of the OSPF protocol.

## Connections problems

Due to dual virtualization of network interfaces (emulation of Debian interfaces by VirtualBox and emulation of Cisco router interfaces from part of the IOS emulator), it might happen that there are 2 identical MAC addresses, as they are randomly generated on startup. To mitigate this problem just restart the virtual machine which is unreachable to generate a new MAC address.
