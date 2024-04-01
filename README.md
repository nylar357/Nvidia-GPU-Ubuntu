Update : Currently working with 
# ubuntu 18.04-Current 
# Kubuntu 18.04-Current 
# Zorin 
# PopOS 
# Garuda
 
 
   # ㄩ尸ᗪ闩七🝗ᗪ : 千㠪乃 己0己㇌
 
![preview](imgs/nvidia.png)


![preview](imgs/nvidia2.png)
![preview](imgs/kubuntu.png)

Proper Installation of Nvidia Drivers on Ubuntu 18.04 (tested and confirmed).  EDIT Working up to 23.04

![preview](imgs/whole2.png)

![prevuew](imgs/screen.png)
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

![preview](imgs/fps2.png)



