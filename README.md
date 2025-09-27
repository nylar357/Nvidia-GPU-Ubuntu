Update : Currently working with Ubuntu 24 LTS PopOS 22 & 24
 
 
   # ㄩ尸ᗪ闩七🝗ᗪ : September 2025
 
![preview](imgs/nvidia.png)
![preview](imgs/nvidia2.png)
![preview](imgs/popos2.png)


## Step 1 First comes first, lets get your drivers ##

https://www.nvidia.com/en-in/drivers/

## Step 2 Make your driver executable ##

```chmod +x driver.run```

## Step 3 Install depends (which should be installed by default on 18.04) ##

```sudo apt-get install gcc & cmake```

## Step 4 start the installation, continue to install anyway if prompted, at the end you do not want to edit ##

```sudo bash driver.run```

## answer how your system guides, reboot and done! ##

```sudo reboot```

**As of Ubuntu 24 and newer PopOS you no longer have to blacklist.  Also the drviers can be installed in a normal terminal, no need to login terminal only.**





