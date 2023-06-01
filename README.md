# TITLE - Home Server

In this tutorial I will guide you to how to create a home server in your old laptop using Ubuntu.

-> First install Ubuntu's latest server version in thier official website.

![2023-06-01_13-08](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/fb9db921-1f29-4cc9-873b-76c00d9a5c46)

-> After downloading the iso image falsh into a pendrive (minimum 8gb) using any flashing apps. Recommend Balena Etcher it will look like the below image. Download and flash the ubuntu iso image.

# Screenshot of Etcher

![etcher](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/6ec82770-3fd2-4f37-a4c4-9817be44ce81)

-> Then plug the pendrive in you old laptop and turn on. Then press the boot menu button (commonly f2 or f12). 

-> After the boot menu appears click your pendrive name in the listed options.

-> It will look like the below image after you clicked it.

# Boot Image

![boot](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/c02364d2-7edd-4a10-8708-a855a1ed7e3c)

-> Click Try or Install Ubuntu server.

-> Then complete the setup.

![lang](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/f6bec5ce-6908-4e12-9eab-efcea0e89bc3)

-> If you want your server to run 24/7 click the ubuntu server or click ubuntu server (minimized).


![server](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/e6b1ae68-f7af-4b97-b6ad-05aca014820b)

-> Now setup your network connection. As I told, if you decided to run your server 24/7 ethernet is great option as it won't disconnect like wifi.

# Network Settings

![network](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/6f91871c-a4c5-46be-bc48-1b5bc00f0c9c)

-> Once you finished your network setup it will show you proxy setup. Don't type anything in it just click done.

-> After that it will show you mirror address,don't change anything on it just click done. 

# Storage settings

-> Click use entire disk in the option as shown below. Unclick use this device as an LVM group then click done.

![storage](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/948bdb2d-bd58-489b-8a41-874048557206)

-> Once you finished the storage setup it will show you a screen like below.

![storage config](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/72f2b536-304d-4c4d-b50a-b431ece1f0bf)

-> Just click done then continue.

# Profile Setup

-> Setup your profile like username, servername and password.

![profile setup](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/d0e0d798-4d67-4677-af35-676da7fdcbca)

-> Once you completed your profile setup it will show you SSH setup screen like below.

![ssh](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/83292543-6bc0-4373-a9fa-7c7bab837f82)

-> Click install open ssh server and click done.

# We are only one step ahead !!

![snaps](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/6cb28c60-3744-44fa-bf73-d1e58d407762)

-> We don't require any of these so click done.

-> By this time your pc will start to install the server like below.

![install setup](https://github.com/akash-karthikeyan-linux/Home-Server/assets/65849775/483b6234-e82c-4db8-b4a5-8033015a1eeb)

-> Once it shows "reboot now" option like the above image click it and remove your pendrive from your pc. 

-> The pc will start to reboot and boot into ubuntu server.

-> Once it is booted into Ubuntu server you are required to type your username and password which you typed in the profie setup. Then BOOM !!! YOU ARE IN YOUR HOME SERVER !!!

# COPY THESE CODES AND PASTE IN YOUR HOME SERVER TO MAKE IT FULLY FUNCTIONAL

command : sudo apt update

-> You need to type the password you created after you run this "sudo apt update" command. If it asked (yes/no) click "y"

-> Then you need to type "sudo apt upgrade" 

-> These commands are used to update your ubuntu version upto date.

# Installing SAMBA

-> After running these commands type "sudo apt install samba"



 
 
