# RaspberryPi_AutoStart
Repo detailing the process of automatically running apllcaitons on boot on a Raspberry Pi running Debian

## Process

open a terminal and run the following commands. Theses commands will create a folder named 'autostart' in the hidden '.config' folder of the Raspberry Pi's OS. This 'autostart' folder will hold the '.desktop' file which will run the application on booting up the device. A sample '.desktop' file is available in this repo and should be modified in line with the given application.
The final line below will open the Nano Text Editor were the '.desktop' file can be created or edited. 

1)        sudo mkdir .config/autostart      
2)        cd .config/autostart
3)        nano My_App.desktop
  



## More Details Available:
https://www.geeks3d.com/20191122/how-to-create-a-shortcut-on-the-raspbian-desktop/
