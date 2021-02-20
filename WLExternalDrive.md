# How to - Partition and Format an External Drive for Linux and Windows
## Steps
1. Without external drive inserted Type "sudo blkid | grep UUID" to list the internal drives
2. Insert drive into USB
3. Type "sudo blkid | grep UUID" to list internal and external drives, compare to the output from step 1 to find the details of the external drive. Typically something like:
4. <br>
/dev/sda1: LABEL_FATBOOT="distro" LABEL="distro" UUID="65FD-01C1" TYPE="vfat" PARTUUID="882e45ef-01"

