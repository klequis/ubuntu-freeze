Does it have a GPT identifier and is all of the space partition free and unallocated?

MemTest86

BIOS is updated

Pop!OS 22.04

@dick same problem with a core 2 duo and nvidia 510 driver.after using ALT-PrtScr-B booting it no longer freezes.

 Kernel 5.15.40 freezes
 
 5.17, 4 minutes in and no freeze yet 
 
 free -m
 
 sudo lshw -short
 
 sudo journalctl  -b -1 -e
 
 swapon -s
 
 ubuntu-bug gnome-shell
