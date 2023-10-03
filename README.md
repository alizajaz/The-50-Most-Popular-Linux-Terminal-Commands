# The-Most-Popular-Linux-Terminal-Commands
The 50 Most Popular Linux &amp; Terminal Commands

Windows Powershell> wsl --install>you will see this message > then reboot 
Installing: Virtual Machine Platform
Virtual Machine Platform has been installed.
Installing: Windows Subsystem for Linux
Windows Subsystem for Linux has been installed.
Installing: Windows Subsystem for Linux
Windows Subsystem for Linux has been installed.
Installing: Ubuntu
Ubuntu has been installed.
The requested operation is successful. Changes will not be effective until the system is rebooted.
PS C:\Users\Admin>

**WslRegisterDistribution failed with error: 0x80370102**********
**if you get error like this 
WslRegisterDistribution failed with error: 0x80370102
Please enable the Virtual Machine Platform Windows feature and ensure virtualization is enabled in the BIOS.
For information please visit https://aka.ms/enablevirtualization
Press any key to continue...**
https://answers.microsoft.com/en-us/windows/forum/all/wslregisterdistribution-failed-with-error/5fdd8aa6-175e-4a14-8fe6-07673133fd15 



Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\Admin> wsl --update
Checking for updates.
The most recent version of Windows Subsystem for Linux is already installed.
PS C:\Users\Admin> wsl --set-default-version 1
The operation completed successfully.
PS C:\Users\Admin> wsl --install -d Ubuntu
Ubuntu is already installed.
Launching Ubuntu...
Installing, this may take a few minutes...
Please create a default UNIX user account. The username does not need to match your Windows username.
For more information visit: https://aka.ms/wslusers
Enter new UNIX username: tttt
New password:
Retype new password:
Sorry, passwords do not match.
passwd: Authentication token manipulation error
passwd: password unchanged
Try again? [y/N] y
New password:
Retype new password:
passwd: password updated successfully
The operation completed successfully.
Installation successful!
To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

Welcome to Ubuntu 22.04.2 LTS (GNU/Linux 4.4.0-19041-Microsoft x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

This message is shown once a day. To disable it please create the
/home/aliza/.hushlogin file.
aliza@DESKTOP-aliza:~$ sudo su
[sudo] password for aliza:
root@DESKTOP-aliza:/home/aliza# apt-get update





