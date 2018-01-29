# NdisProtocol
Windows NDIS 6.3 Protocol Driver that provides usermode access to an IsoSwitch or CrowdSwitch

This is based mostly on the Windows Driver Kit ndisprot63 sample driver. It has been customized to allow communication only on the IsoGrid 0x6500 EtherType, and handles the MAC addresses in Kernel Mode.

Currently, this driver is available for use by non-elevated processes. However, eventually this driver will instead be used to build up a more formal NT service that controls the physical IsoSwitch.
