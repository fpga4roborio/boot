To build PetaLinux image, run mkimage -f new_image.its image.ub

NOTE: The initrd is not recommended to put into the FIT boot image (image.ub file). Instead, extracting it to a blank ext4 partition and set kernel parameter `root` to point to the partition is recommended (you have rw access and persistent storage).
