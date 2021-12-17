# laptop_issues
issues found with some laptops i have used

1. asus n55sf, i5-2410 processor.
-it is expected to accept only 8GB RAM but 16GB it will work wheel 

 -under linux audio is partial working on old kernels (less than 4.0.x ) (see archlinux info about implementation status ). there are also some issues with nvidia 555M - possible fixed in recent kernels
 
-big uefi sleep bug -need more investigation: If you boot linux/windows (7,10)in UEFI mode (UEFI enabled in BIOS) it could not go to sleep, instead it hang (before entering to sleep ) and you must shutdown (press power more than 3 seconds). If in normal mode (legacy, uefi disabled in BIOS), it will work as expected.

-in UEFI mode, under windows, the intel audio driver does not work (as 2018.01.27). Under linux (ubuntu 17.10.1) it will work.




2. lenovo b50-70, i5

unexpected, the laptop will POST using random time: on power on, the hdd and cooler will spin-up but the screen will stay black indefinitely. The power led and hdd led will blink: hdd led 6 blinks shorts, power one blink. After random time (hours sometimes) the computer will start, as nothing had happend. The same apply if use "enter to bios" hidden button near usb port on right side.

presumed the bug is related to intel SPI bug, but not sure. Bios upgrade do not work at this time (2018.01.27).


3. asus S15  System Model	X510UQR
Processor	Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz, 1992 Mhz, 4 Core(s), 8 Logical Processor(s)


no issues at this time.  the maximum memory for the processor can be installed (32GB).
It have support for  both SATA and M2 SSD, curently 2TB SATA and 1TB M2

