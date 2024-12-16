### Intel IGC Driver for Intel(R) I225-LM/I225-V 2.5G Ethernet Controller.

This driver was migrated from Linux 5.10.0 and is tested on Linux 5.4.0. **Please use it at your own risk.**

How to use:
1. CLone this repository.
2. Copy to the source codes to your target machine.
3. Build this module
```c
make host
```
4. Then, insert this module:
```c
sudo insmod igc.ko
```

Then, you could check the network status with `ifconfig`. Otherwise, you can use `dmesg` to see logs.
