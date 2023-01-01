![Arch Linux Secure AF](./archLinux.png)
## Awesome Arch Linux
A collection of my shell scripts with hardened Arch Linux installation, configuration, security tweaks and more.
The idea is to make this repo a reliable and curated reference to Arch Linux hardened installation, hardening set ups, and configurations.

The encryption method use in the installation script is [LVM on LUKS with encrypted boot partition](https://wiki.archlinux.org/title/Dm-crypt/Encrypting_an_entire_system#Encrypted_boot_partition_(GRUB))(Full disk encryption).

First downaload Arch ISO [here](https://archlinux.org/download/)

Boot the media on the target device you want install Arch linux.

To run the base scripts on your machine, all you need to do is:

1. Have both **archinstall.sh** and **chroot.sh** on the same directory.
2. Edit the variables on both files: your target device, username...
3. chmod +x **archinstall.sh** and **chroot.sh**
4. Then run **archinstall.sh** like so: ./archinstall.sh
