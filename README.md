# GUIDE to Born2BeRoot

Hey, this is my first time touching Linux and using an OS without a graphical interface. So if you are experiencing the same, have a read!
But, I ain't an expert in this, so be aware of that fact. There might be some errors.

#### Some cool stuff you can do to improve your workflow and experiment with the code later is to take snapshots and revert back to the versions that you did not understand or where you have worries that you did an incorrect setup.

<img width="893" alt="Screen Shot 2022-11-29 at 7 00 28 PM" src="https://user-images.githubusercontent.com/49612380/204608711-88c13899-1bf7-4dd1-8bd3-ae1c15766269.png">

##### Some extra reading material 

##### https://www.debian.org/intro/why_debian

##### https://www.openlogic.com/blog/centos-vs-debian 

##### The basic summary:


1. Debian, also known as Debian GNU/Linux, is a GNU/Linux distribution composed of free and open-source software, developed by the community-supported Debian Project.

2. CentOS is a Linux distribution that strives to provide a free enterprise-class computing platform that has 100% binary compatibility with its upstream source, Red Hat Enterprise Linux. It does not support many different architectures. This should make it very stable and suitable for use as a web server.

3. Debian is an operating system produced by the Debian project, mostly comprised of free and open-source software, adhering to the GNU General Public License. However, it also includes non-GPL software outside its official repositories to comply with its guidelines for implementing free software. Debian has less market share compared to other operating systems. A new version of Debian is usually released with a 2-year gap between releases, focusing on bug fixes. Hence, these systems are more reliable and long-lasting.

4.Debian has many more packages in its default repositories than CentOS.

 ### Seting up the Debian ###

<img width="968" alt="Screen Shot 2022-11-28 at 3 37 26 PM" src="https://user-images.githubusercontent.com/49612380/204305852-b26f4427-b371-442a-9a30-568a42e337a6.png">


<img width="1269" alt="Screen Shot 2022-11-28 at 3 36 44 PM" src="https://user-images.githubusercontent.com/49612380/204305866-49c01ff0-8d7e-40c8-845a-88426f38a84b.png">

#### Choose 8 GB for task withhout bonus and 30.8 for Bonus ####

<img width="969" alt="Screen Shot 2022-11-28 at 3 37 55 PM" src="https://user-images.githubusercontent.com/49612380/204305872-eb9919d0-5010-4e96-8117-1437679a2661.png">


<img width="1274" alt="Screen Shot 2022-11-28 at 3 38 54 PM" src="https://user-images.githubusercontent.com/49612380/204305875-0e5e289f-067f-43dc-8be1-d9b2730f3692.png">


<img width="959" alt="Screen Shot 2022-11-28 at 3 39 24 PM" src="https://user-images.githubusercontent.com/49612380/204305877-b427fc13-7926-4d90-bdaa-266a4c5bd753.png">

#### Language choose english and take the central region germany, UTF -8 American English

### Seting up the user and password ###

<img width="1200" alt="Screen Shot 2022-11-28 at 3 41 13 PM" src="https://user-images.githubusercontent.com/49612380/204306080-a0dbd712-635b-4e35-a81f-05d3f9369025.png">

### Seting up the partions ###

<img width="1192" alt="Screen Shot 2022-11-28 at 3 45 32 PM" src="https://user-images.githubusercontent.com/49612380/204306524-c7b63958-6836-4df1-96c9-bf0aa7c05b9d.png">

#### 1.Press guided
#### 2.Select to create all 3 folders 
#### 3.Press yes ####

<img width="1196" alt="Screen Shot 2022-11-28 at 3 49 14 PM" src="https://user-images.githubusercontent.com/49612380/204307338-5f9337c8-e509-4a7b-82a0-1c43f59394a7.png">


#### Set up the encryption

#### Type max in Partition disks 

<img width="1197" alt="Screen Shot 2022-11-28 at 3 51 54 PM" src="https://user-images.githubusercontent.com/49612380/204307918-ff5b4181-ac13-443a-b470-c2f5f4524633.png">

<img width="1195" alt="Screen Shot 2022-11-28 at 3 52 43 PM" src="https://user-images.githubusercontent.com/49612380/204308215-89e3918a-3361-400e-9fc9-878dde46e0f6.png">

#### Finish

<img width="1195" alt="Screen Shot 2022-11-28 at 3 52 43 PM" src="https://user-images.githubusercontent.com/49612380/204309139-bd1bf978-4a30-4ec6-8c34-af4fff46940e.png">
#### Yes

<img width="1200" alt="Screen Shot 2022-11-28 at 3 55 59 PM" src="https://user-images.githubusercontent.com/49612380/204309186-d86584fc-aa14-45aa-ad36-acc5842f99d7.png">

<img width="1202" alt="Screen Shot 2022-11-28 at 3 56 22 PM" src="https://user-images.githubusercontent.com/49612380/204309208-01daef72-3a35-47d1-a81c-4c8912ab79e9.png">

<img width="1198" alt="Screen Shot 2022-11-28 at 3 57 40 PM" src="https://user-images.githubusercontent.com/49612380/204309416-92ae659a-ea49-4407-927b-b7c17035474e.png">

<img width="1203" alt="Screen Shot 2022-11-28 at 4 02 54 PM" src="https://user-images.githubusercontent.com/49612380/204311153-0bbce28f-912b-4207-85b2-4e8989e6da74.png">

<img width="1201" alt="Screen Shot 2022-11-28 at 4 03 20 PM" src="https://user-images.githubusercontent.com/49612380/204311164-4dff4f0d-1167-43fb-82c8-f467c0f74c53.png">

<img width="1192" alt="Screen Shot 2022-11-28 at 4 05 06 PM" src="https://user-images.githubusercontent.com/49612380/204311168-47167555-19a0-4fbe-8d54-dc04cc5cd7af.png">

### And Voila you have setup VM with Debian OS

#### For more efficient work to move mouse from VM to your Mac hold command button.

Run 

#### Command to run lsblk ####

<img width="1190" alt="Screen Shot 2022-11-29 at 1 00 16 PM" src="https://user-images.githubusercontent.com/49612380/204523773-9d1a4694-3219-494e-833e-163a9d75f71a.png">

#### lsblk runs and lists aviable information about all aviable specific block devices (except RAM disks) ####

## Install the things you will need for the project

#### APT installation 

Advanced Package Tool, more commonly known as APT, is a collection of tools used to install, update, remove, and otherwise manage software packages on Debian and its derivative operating systems, including Ubuntu and Linux Mint.

Alternative is 

#### Aptitude

Aptitude is a text-based interface to the Debian GNU/Linux package system. It allows the user to view the list of packages and to perform package management tasks such as installing, upgrading, and removing packages. Actions may be performed from a visual interface or from the command-line.

##### 1. su - 
switches between users 

su , on the other hand, is an acronym for switch user or substitute user. You are basically switching to a particular user and you need the password for the user you are switching to. Most often, the user account you switch to is the root account but it can be any account on the system.

##### 2. apt-get update -y // Install and updates the pacages for each outdated system
##### 3. apt-get upgrade -y // Confirms the updates

#### Sudo installation

sudo is a program for Unix-like computer operating systems that enables users to run programs with the security privileges of another user

##### 4. apt install sudo

<img width="1205" alt="Screen Shot 2022-11-29 at 1 21 38 PM" src="https://user-images.githubusercontent.com/49612380/204528866-29218142-5b62-4577-947f-3b9e290382dc.png">

#### Install Git

##### 5. apt-get update -y
##### 6. apt-get upgrade -y
##### 7. apt-get install git -y

Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

<img width="1205" alt="Screen Shot 2022-11-29 at 2 48 40 PM" src="https://user-images.githubusercontent.com/49612380/204546068-c51568b9-1ffa-4990-9a30-359ab8b9fffb.png">

##### VIM

Vim is the editor of choice for many developers and power users. It's a “modal” text editor based on the vi editor written by Bill Joy in the 1970s for a version of UNIX. It inherits the key bindings of vi, but also adds a great deal of functionality and extensibility that are missing from the original vi.

##### 8. sudo apt-get install vim

##### 9. sudo apt-get update
##### 10. sudo apt install openssh-server

#### UFW

What is UFW? UFW, or uncomplicated firewall, is a frontend for managing firewall rules in Arch Linux, Debian, or Ubuntu. UFW is used through the command line (although it has GUIs available), and aims to make firewall configuration easy (or, uncomplicated).

##### 11. apt-get install ufw

#### libpam-pwquality

libpwquality's purpose is to provide common functions for password quality checking and also scoring them based on their apparent randomness. The library also provides a function for generating random passwords with good pronounceability.

##### 12. sudo apt-get install libpam-pwquality

##### AppArmor https://linuxhint.com/debian_apparmor_tutorial/ 
If you are using Debian 10 "Buster" or newer, AppArmor is enabled by default so you can skip this step.

Install the NetTools

The Net-tools package is a collection of programs for controlling the network subsystem of the Linux kernel. This package is known to build and work properly using an LFS-10.1 platform.

##### 13. sudo apt-get update -y
##### 14. sudo apt-get install -y net-tools

##### 15. sudo apt-get install cron

The crontab command submits, edits, lists, or removes cron jobs. A cron job is a command run by the cron daemon at regularly scheduled intervals. To submit a cron job, specify the crontab command with the -e flag. The crontab command invokes an editing session that allows you to create a crontab file.

##### 16. App armor

No need to install it

https://wiki.debian.org/AppArmor 
AppArmor is an effective and easy-to-use Linux application security system. AppArmor proactively protects the operating system and applications from external or internal threats, even zero-day attacks, by enforcing good behavior and preventing both known and unknown application flaws from being exploited.

## Config of the machine

##### 1. adduser username sudo (Must be in -su)
adds user to the sudo group
##### 2. reboot 
restarts the system
##### 3. getent group sudo
checks for the entities with sudo editing rights
 
<img width="910" alt="Screen Shot 2022-11-29 at 3 58 29 PM" src="https://user-images.githubusercontent.com/49612380/204563501-ee67de89-4797-467b-baa5-87be009de18b.png">
 
##### 4. sudo visudo privilages

The visudo command opens a text editor like normal, but it validates the syntax of the file upon saving. This prevents configuration errors from blocking sudo operations, which may be your only way of obtaining root privileges. Traditionally, visudo opens the /etc/sudoers file with the vi text editor.

Add in the 
 
##### 5. user_name ALL=(ALL:ALL) ALL
 
<img width="939" alt="Screen Shot 2022-11-29 at 5 20 20 PM" src="https://user-images.githubusercontent.com/49612380/204584864-1c5027f1-080a-4121-85e8-3ddc79136ad4.png">

To read the sudoers file on each Linux or UNIX computer, you must have root-level permission. You can define a command right to grant this level of access to other users. The default location for the sudoers configuration file is /etc/sudoers, and in general, this is the file to import from each computer.
 
 
##### "sudo reboot" usefull command

The requiretty option means that the exploit code won't be able to directly upgrade its privileges by running sudo.

##### 6. passwd_tries = 3, badpass_message="text", requiretty logfile="/var/log/sudo/sudo.log", log_input, log_output
 

There might be a situation that you do not have a sudo folder, so you can create it here.  
##### /var/log/sudo
 
 <img width="980" alt="Screen Shot 2022-11-30 at 10 58 10 AM" src="https://user-images.githubusercontent.com/49612380/204765777-509bf082-952b-4ea6-b7a5-2fca50697a9c.png">

The terminal is also represented as a file. There a command exists called tty which displays information related to terminal. The tty command of terminal basically prints the file name of the terminal connected to standard input

##### 7. sudo systemctl status ssh
Check if the ssh is working $ 
##### 8. sudo service ssh restart
Reboot ssh 

##### 9. sudo nano /etc/ssh/sshd_config
Change port names from 22 to 4242

<img width="1197" alt="Screen Shot 2022-11-30 at 9 24 08 AM" src="https://user-images.githubusercontent.com/49612380/204745198-a2bc7b36-a886-4e31-a239-31e9016b09f9.png">


##### Do not forget to uncoment it

![image](https://user-images.githubusercontent.com/49612380/204799189-3c9b045c-2582-47e2-82e5-b651a6dc2f20.png)


##### 10. sudo grep Port /etc/ssh/sshd_config
##### 11. sudo service ssh restart
Check if the config is correct

<img width="672" alt="Screen Shot 2022-11-30 at 9 26 06 AM" src="https://user-images.githubusercontent.com/49612380/204745925-6202acd5-6f86-4274-93fc-da2e48b8e897.png">


##### 12. sudo ufw enable
Turn on the firewall

##### 13. sudo ufw status numbered
Checks the status of the firewall

##### 14. sudo ufw allow ssh
Adds a rule to the firewall that allows the use of ssh

##### 15. sudo ufw allow 4242
Allows connection to the port 4242

<img width="938" alt="Screen Shot 2022-11-30 at 9 35 04 AM" src="https://user-images.githubusercontent.com/49612380/204747064-b879e5f0-4abf-4a80-8984-b316d3cc359b.png">

##### 16. sudo ufw status numbered

<img width="931" alt="Screen Shot 2022-11-30 at 12 53 54 PM" src="https://user-images.githubusercontent.com/49612380/204790441-9d2e15b4-2866-4642-8d92-656ae2088940.png">

##### 17. sudo ufw delete number

<img width="939" alt="Screen Shot 2022-11-30 at 12 57 12 PM" src="https://user-images.githubusercontent.com/49612380/204790456-175a195e-b0a6-4974-ab4e-05ce5576564f.png">

Delete usless ports

##### 18. Port Forwarding in VM Advanced settings

Forward rule to VM

<img width="613" alt="Screen Shot 2022-11-30 at 1 01 41 PM" src="https://user-images.githubusercontent.com/49612380/204791689-f7d1b8b6-dec7-4775-b96e-0ab74ae7928a.png">

<img width="803" alt="Screen Shot 2022-11-30 at 1 02 30 PM" src="https://user-images.githubusercontent.com/49612380/204791709-13e84403-95ff-47ae-938d-417769877744.png">

Add the port for connection

##### 19. sudo systemctl restart ssh
##### 20. sudo service sshd status


<img width="843" alt="Screen Shot 2022-11-30 at 1 10 27 PM" src="https://user-images.githubusercontent.com/49612380/204792826-1f744cc1-080a-44b3-818f-8c9c66de0c93.png">


If all went well you should be able to connect your VM to the terminal

##### 21. ssh [your_name]@127.0.0.1 -p 4242

<img width="564" alt="Screen Shot 2022-11-30 at 2 31 13 PM" src="https://user-images.githubusercontent.com/49612380/204809412-e846dfce-256d-4fdf-a33c-0bc757eada8e.png">

##### 22. exit
To stop connection

#### Password config!

go to 
##### 23. sudo nano /etc/pam.d/common-password 

<img width="1202" alt="Screen Shot 2022-11-30 at 2 55 28 PM" src="https://user-images.githubusercontent.com/49612380/204814603-7dca10dc-faea-47b5-b3d1-71f941069b66.png">

##### Do not have spaces after the 

Add

##### 24. minlen=10
to the end of the [sucess=1 default=ignore] in 

and add 

##### 25. lcredit=-1 ucredit=-1 dcredit=-1 maxrepeat=3 usercheck=0 difok=7 enforce_for_root

go to 
##### 26. sudo nano /etc/login.defs

and switch the preset dates 9999, 0, 7 to 

<img width="262" alt="Screen Shot 2022-11-30 at 3 04 01 PM" src="https://user-images.githubusercontent.com/49612380/204816430-3673c23d-85ba-42eb-a006-467e2cda5d89.png">

#### No spaces between the characters (the password manager won't work then)

##### 27. sudo groupadd user42
##### 28. sudo groupadd evaluating

you can check if it was success with 

##### 29. getent group

<img width="527" alt="Screen Shot 2022-11-30 at 3 23 30 PM" src="https://user-images.githubusercontent.com/49612380/204821278-e166b394-f084-4696-999c-529defea677f.png">

sudo adduser <username> user42

### Woho now the script part

## Script and the setup of the script

##### 1. sudo crontab -u root -e
 
Here you will write the script!

##### Choose VIM, or whatever that you can work with
 
<img width="854" alt="Screen Shot 2022-12-01 at 9 59 46 AM" src="https://user-images.githubusercontent.com/49612380/205010340-e3e2f188-4f57-47b5-b79b-a80f95009bbf.png">

##### 2. */10 * * * * * /path/monitoring.sh
Add your required time and path to the file, crontab file explenations, in short explenations of the starts (min, hour, day, specific day of month, specific month, specific day)

<img width="680" alt="Screen Shot 2022-12-01 at 10 00 10 AM" src="https://user-images.githubusercontent.com/49612380/205010372-5129d335-32e0-465d-9ff1-b177db396aba.png">
 
As a bonus I added an 
##### Just an idea of log backup, not important tho. /usr/local/bin/monitoring.sh > /usr/local/bin/monitoring.txt 2>&1
Key notes for work in VIM 

##### A or E, start writing in Vim
##### Esc for stoping work in Vim
##### :wq for save and quit
##### :q for quit
##### :q! for quit and not save

##### 3. Go to your monitoring.sh file and start editing it
## THE SCRIPT
 

echo - echo will print output, but it will often disappear by the time your script is done.
awk - Mostly used for pattern scanning and processing
NR - Number of Records (special command for awk)
NF - a predefined variable whose value is the number of fields in the current record. awk automatically updates the value of NF each time it reads a record. No matter how many fields there are, the last field in a record can be represented by $NF 

 <pre>
#!/bin/bash

echo -n -e "Architecture: "; uname -a
echo -n -e "CPU : "; grep -c ^processor /proc/cpuinfo
echo -n -e "vCPU : "; cat /proc/cpuinfo | grep processor | wc -l
echo -n -e "Memory usage: ";  free -m | awk 'NR==2{printf"(%s", $3}'
echo -n -e "/"; free -m | awk 'NR==2{printf"%s)MB", $2}'
echo -n -e "  "; free | awk 'NR==2{printf"(%.2f%%)\n", $3/$2*100}'
echo -n -e "Disk usage: "; df -h | awk 'NR==4{printf "(%.2f", $3}'
echo -n -e "/"; df -h | awk 'NR==4{printf "%.2f)GB", $2}'
echo -n -e "  "; df -h | awk 'NR==4{printf "(%s)\n", $5}'
echo -n -e "CPU load:  "; top -bn1 |grep load | awk '{printf "%.2f%%\n", $(NF-2)}'
echo -n -e "Last boot: "; who | awk '{printf $3 " " $4 "\n"}'
echo -n -e "Number of LVM's:"; if lsblk | grep "lvm" | wc -l; then echo -n -e "LVM use: Yes\n"; else echo -n -e "LVM use: No\n"; fi
echo -n -e "Connections TCP: "; cat /proc/net/tcp | wc -l | awk '{printf $1 - 1" ESTABLISHED\n"}'
echo -n -e "User log: "; w | wc -l | awk '{printf$1 - 2 "\n"}'
echo -n -e "Network: IP "; ip route list | grep link | awk '{printf $9}'
echo -n -e "  "; ip link show | grep link/ether | awk '{printf $2 "\n"}'
echo -n -e "#Sudo: ";cat /var/log/sudo/sudo.log | wc -l | tr '\n' ' ' && echo "cmd";
printf "\n"
</pre>
 
###### To display this commands you need to go to your crontab 

 <pre>
*/10 * * * * /usr/local/bin/monitoring.sh | wall
*/10 * * * * /usr/local/bin/monitoring.sh > /usr/local/bin/monitoring.log 2>&1
 </pre>
 
And you should be done! 

## Important commands

###### sudo ufw allow port - allow port to the firewall
###### sudo ufw - firewall
###### sudo ufw status numbered 
###### sudo ufw delete - delete firewall permision
###### cd - move in a folder
###### cat - display the text 
###### /var/log/sudo - file location of log out put
###### su- changes the privilages
###### sudo visudo - checks the sudoers file
###### lsblk - checks the machines partions
###### sudo adduser [username] [group] - adds user to the grou
###### getent group [group] for example user42 and evaluating 
###### sudo adduser [new_username] - adds user to the machine
###### sudo deluser [user_name] [group] - deletes user from the group or machine
###### ip addr -- checks the ip adddres of the machine
###### hostnamectl -- check out the host
###### hostnamectl set-hostname
###### passwd [user_name] - change the password of the pax
###### getent group
 
 

