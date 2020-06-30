Proper Installation of Nvidia Drivers on Ubuntu 18.04 (tested and confirmed).

[!orevuew](img/screen.png)
Make your driver executable

$ chmod +x driver.run

Install depends (which should be installed by default on 18.04)

$ sudo apt-get install gcc & cmake

Blacklist the Nouveau drivers in kernel

$ sudo bash -c "echo blacklist nouveau > etc/modprobe.d/blacklist-nvidia-nouveau.conf"

$ sudo bash -c "echo options nouveau modset=0 >> etc/modprobe.d/blacklist-nvidia-nouveau.conf"

Update Kernel with the Blacklist

$ sudo update-initramfs -u

Reboot

$ sudo Reboot

Terminal only login (perform at login screen)

$ Ctrl+Alt+F3

Login to the terminal only mode, then install Drivers

$ sudo telinit 3

$ sudo bash driver.run

answer how your system guides, reboot and done!

$ reboot

ESO Running With Lutris

[!preview](img//Screenshot from 2020-06-30 00-44-49.png)
