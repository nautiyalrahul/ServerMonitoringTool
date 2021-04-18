# ServerMonitoringTool
A tool to fetch basic details for a linux based system

Setup Details:=
           1. Linux server:- CentOS virtual machine with sshd service enabled
           2. Text editor:- Atom

Tip:-
           1. Make sure that the server is up and pingable
           2. Make sure that ssh service is enable for the server

Steps:- 
           1. Install paramiko module with pip installer
           2. Store the files i same folder and run the main tool file

Files:-
           1. ConnectEstablish.py --> Code for establishing connection
           2. Variables.py  --> Contains the server IP and the commads 
           3. MainTool.py  ---> Code to print the outpu of the commands

Output:-
  ================================================== pwd ==================================================
/root

================================================== id ==================================================
uid=0(root) gid=0(root) groups=0(root) context=unconfined_u:unconfined_r:unconfined_t:s0-s0:c0.c1023

================================================== uname -a ==================================================
Linux localhost.localdomain 4.18.0-240.el8.x86_64 #1 SMP Fri Sep 25 19:48:47 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

================================================== df -h ==================================================
Filesystem      Size  Used Avail Use% Mounted on
devtmpfs        877M     0  877M   0% /dev
tmpfs           896M     0  896M   0% /dev/shm
tmpfs           896M  9.8M  886M   2% /run
tmpfs           896M     0  896M   0% /sys/fs/cgroup
/dev/sda3        18G  5.1G   13G  29% /
/dev/sda1       295M  173M  122M  59% /boot
tmpfs           180M  1.2M  178M   1% /run/user/42
tmpfs           180M  5.7M  174M   4% /run/user/0


Process finished with exit code 0
