## Dynamic routing protocols

Some problems have been encountered in using the emulator with dynamic routing protocols such as OSPF and RIP. In particular, with the use of RIP, the convergence time in the event of a sudden change in the network topology can be extremely long (even 5 minutes).

The problems described above did not occur with the use of the OSPF protocol.

The problems described above have occurred in a virtual network of 3 routers emulated via VirtualBox and the machine provided in this archive. No tests have been carried out with different network topologies or with the help of physical routers.

## Connections problems

Due to dual virtualization of network interfaces (emulation of Debian interfaces by VirtualBox and emulation of Cisco router interfaces from part of the IOS emulator) can occur equal MAC address cases that cause certain network devices to be unreachable. To resolve this problem simply restart the virtual machine that has the connectivity problem so that the MAC addresses are re-initialized.
