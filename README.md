### Intel IGC Driver for Intel(R) I225-LM/I225-V 2.5G Ethernet Controller.

This driver was migrated from Linux 5.10.0 and was tested on Linux 5.4.0. **Please use it at your own risk.**

How to use:
1. Clone this repository.
2. Copy the source codes to your target machine.
3. Build this module
```c
make host
```
4. Insert this module:
```c
sudo insmod igc.ko
```

Then, you could check the network status with `ifconfig`. If there is still no network controller detected, you could use `dmesg` to see logs.
