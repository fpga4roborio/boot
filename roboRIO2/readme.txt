This directory contains boot files (config, FPGA bitfile, ...) for booting PetaLinux on roboRIO 2.0.

Content:
- minboot/ contains minimal files for booting PetaLinux (with SSH access via Ethernet)
- petalinux/ contains PetaLinux kernel, DTB, and initrd (from which image.ub is assembled)
- src/ contains configs' source code (eg before being turned into their binary form)
- org/ contains original boot files dumped from nibootfs partition (you still need niconfigfs if you want to boot from original images)
