This directory contains minimal boot files for PetaLinux on roboRIO 2.0

!!!NOTE:!!! The uboot directory, along with the uboot.env file inside it, MUST be placed in that way. That is how roboRIO 2.0's u-boot saves its environment variable: to a file on the first partition, at /uboot/uboot.env.

Bonus: The text content of uboot/uboot.env can be dumped by creating a file named fw_env.config with content:
```
./uboot.env 0x0000 0x20000 0x20000
```
and then run fw_printenv -c fw_env.config

This readme.txt file can be deleted if you want to.
