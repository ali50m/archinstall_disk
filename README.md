# issue: the auto partitioning size for /boot is too small
When using auto default ext4 partition option, it will only create 212MB fat32 for /boot.

## 0. environment
- windows 10 pro 21H2 LTSC 19044.4529
- vmware player 17.5.0 build-22583795
- archlinux-2024.06.01-x86_64.iso

## 1. vmware player configuration
![1](pics/1.vmware_config.png)

## 2. arch iso boot menu
![2](pics/2.boot_menu.png)

## 3. update archinstall
![3](pics/3.update_archinstall.png)

## 4. run archinstall & create partitions
![4.1](pics/4.1.main_menu.png)

![4.2](pics/4.2.disk_config.png)

![4.3](pics/4.3.choose_default_layout.png)

![4.4](pics/4.4.select_drive.png)

![4.5](pics/4.5.choose_ext4.png)

![4.6](pics/4.6.choose_default.png)

![4.7](pics/4.7.default_table.png)
