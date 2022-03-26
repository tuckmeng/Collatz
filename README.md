# Minimal Linux Distro

Modified minimal linux live distro https://minimal.idzona.com/#download to use kernel 5.16.12. Isolinux and binaries are currently 2019 version at minimal linux. Original distro at minimal_linux_live_15-Dec-2019_64-bit_bios.iso in https://github.com/ivandavidov/minimal/releases. The iso file is checked at https://www.virustotal.com/gui/file/c96ac0632eb1bf000ed67b7fddc5870b3376aacd159682cd059ed7094dadd5bd?nocache=1 to make sure that it is free from malware.

# Use

Download Qemu for your platform from https://www.qemu.org/download/ and run command qemu-system-x86_64 -boot d -cdrom xxx.iso where xxx.iso is your iso file. Choose option 0 for VGA screen.

# Future Modifications

a. To upgrade the binary packages and harden the distro further by removing functionality from the distro.

b. Replace binaries with faster running equivalents. There are many written in languages other than c++ with improved algorithms, just not very well known yet. 

c. If it gets big enough, to publish it as an official linux distro.
