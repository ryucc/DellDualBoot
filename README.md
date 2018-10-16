# Ubuntu dual boot on Dell Inspiron 14 (128GB SSD + 1TB HDD) 

This is basically the same as other dual boot. The only difference was the installed windows uses AHCI to read disk. Jump to step 3 for details.

Feel free to contact me.

## 1 Create Ubuntu installer USB
0. Prepare a clean USB > 8GB. Backup the data since it will be erased.
1. Get the ubuntu image at Ubuntu website>Ubuntu Desktop>Download
2. (On Windows) Get Rufus [link](https://rufus.akeo.ie/). Open the binary and select your USB and .iso ubuntu image.

## 2 Boot into the USB
0. Turn off windows by holding shift and press poweroff.

## 3 switch windows from RAID to AHCI
Reference: [SOLUTION: Switch Windows 10 from RAID/IDE to AHCI operation](triplescomputers.com/blog/uncategorized/solution-switch-windows-10-from-raidide-to-ahci-operation/
)
**Important** Do this before anything. Else you will need to boot into grub using RAID, then windows will crash.
