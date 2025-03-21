## $${\color {red} \textbf {Operating System}}$$
### operating system is a system software which manages computer resources and acts as an intermediary between a user and the hardware

## $${\color {red} \textbf {Linux vs Windows}}$$
![image](https://github.com/user-attachments/assets/95f501d7-a477-4a71-bc14-90294f6184a7)

![image](https://github.com/user-attachments/assets/53185fc8-0734-4ae1-8f78-3edba120e1e6)



**Linux architecture has four main components hardware,kernel,shell and user/application**

![image](https://github.com/user-attachments/assets/ab950a30-cdbf-4833-9e77-246d3cebbf7a)


**Hardware:** it consists of motherboard ,CPU,HDD etc

**Kernel:** kernel is the heart/core of the OS, kernel communicates with Hardware

**Shell:** provides interface to user to communicate with kernel 

**Application/user:** Users interact with the system through varies applications such as office, games, etc. 


## $${\color {red} \textbf {Directory  Structure in  Linux}}$$

-In Linux directory structure   “/”  (slash) is main directory
- All other directories comes under “/” directory.

![image](https://github.com/user-attachments/assets/b57699df-3ef1-482f-bf0e-1f9f138c4df4)

1. / - The main folder.


2. /bin - Basic commands everyone uses (e.g., ls, cp).


3. /sbin - Commands for system admins (e.g., reboot).


4. /usr - Programs and tools for users.


5. /var - Stores changing files like logs.


6. /tmp - Temporary files that auto-delete.


7. /etc - System settings and configuration files.


8. /dev - Files that connect to hardware (e.g., USB).


9. /proc - Info about running programs and the system.


10. /sys - Details about hardware and devices.


11. /lib - Helper files for programs to run.


12. /boot - Files needed to start the computer.


13. /home - Personal files for each user.


14. /opt - Extra programs you install.


15. /root - Personal files for the admin.


16. /media - Automatically mounted drives (e.g., USB).


17. /mnt - Manually mounted drives.


18. /srv - Files for server programs (e.g., websites).


19. /run - Temporary system files from this boot.
    
## $${\color {red} \textbf {Basic Linux Commands}}$$


- switch to root user
```
sudo -i
````
- check current shell
````
echo $SHELL
````
- check kernel information
````
uname -a
````
- check os information
````
cat /etc/os-release
````
- check free memory
````
free -h
````
- check disk/storage information
````
df -h
````
- list block devices
```bash
lsblk
```
- check size of file/dir
````
du -sh file/dirname
````
- list files
````
ls
````
- change directories
````
cd dirname
````
- move to previous directory
```bash
cd ..
```
- check current directory
````
pwd
````
- check live processes
````
top
````
- check CPU information
```bash
lscpu
```

- exit the terminal
```bash
exit
```
