# OS_Project

Kernel is central component of an operating system that manages operations of computer and hardware. It basically manages operations of memory and CPU time. It is core component of an operating system.

<b>Objectives of Kernel</b>:<br>
•	To establish communication between user level application and hardware.<br>
•	To decide state of incoming processes.<br>
•	To control disk management.<br>
•	To control memory management.<br>
•	To control task management.<br>

•	<b>GNU/Linux</b> – We are using GNU/Kali Linux 2017 i386 distribution .<br>
•	<b>Assembler</b> – We are using GNU Assembler(gas) to instruct the bootloader for loading the starting point of our kernel.<br>
•	<b>GCC</b> - GNU Compiler Collection a cross compiler. A newer version of GCC. I am using 7.2.0 version of GCC. The most important thing.
If you use old version you may face multiboot header not found error.<br>
•	<b>Xorriso</b> - A package that creates, loads, manipulates ISO 9660 filesystem images.(man xorriso)<br>
•	<b>grub-mkrescue</b> - Make a GRUB rescue image, this package internally calls the xorriso functionality to build an iso image.<br>
•	<b>QEMU</b> - Quick EMUlator to boot our kernel in virtual machine without rebooting the main system.<br>
