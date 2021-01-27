                           SunflowerOS					26-Jan-2021|Debian10
		      "a source code project"
			       by:
		Scott Cyber Ops & Risk Management ©

	You can't do much until you burn a SunflowerOS CD/DVD from the ISO file
and boot it, or you aim your virtual machine's CD/DVD at the ISO file
and boot.
	SunflowerOS files are compressed and the source code can only be 
compiled by the SunflowerOS compiler. It becomes available when you boot
the CD/DVD. 

**********SunflowerOS is 100% open source with all source present.**********

***SunflowerOS is 64-bit and will not run on 32-bit hardware.

****SunflowerOS requires 999MB of RAM minimum.

SunflowerOS may require you to enter I/O port addresses for the CD/DVD drive
and the hard drive.
	***FOR WINDOWS***-In Windows, you can find I/O port info in the
	Accessories/System Tools/System Info/Hardware Resources/I/O ports.
	Look for and write down "IDE", "ATA" or "SATA" port numbers.
	***FOR LINUX*** -In Linux, use
	"lspci -v".  Then, boot the SunflowerOS CD and try all combinations. 
(I apologize that, it's too difficult for SunflowerOS to figure-out port numbers, automatically. After all we just planted the seed and development is in its earliest stages!)

The source code can also be found at the TempleOS web site, 
http://www.templeos.org but CANNOT be compiled outside of SunflowerOS because
it's HolyC, a non-standard C/C++ dialect, and 'asm' and is only used by SunflowerOS & it's father TempleOS.
