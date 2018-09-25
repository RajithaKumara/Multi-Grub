# Multi-Grub

This is a example for create multiple [GRUB](https://www.gnu.org/software/grub/) entry for multiple operating systems(OS) on single drive. This example contain following operating systems
* CentOS 7
* Debian 9.5.0
* Ubuntu 18.04.1 

## Usage
* First clone the repository.
``` bash
$ git clone https://github.com/RajithaKumara/Multi-Grub
```
* Goto `dev-sda1(FAT16)` directory.
* Copy `EFI` folder to UEFI drive. And drive should be formated to FAT-12/16/32.
* Goto `dev-sda2(Ext4)` directory.
* Copy `boot` folder into Ext4 formated drive. Rename that drive label to 'Ubuntu'.
* Replace particular `grub.cfg` file with each OS folder.
