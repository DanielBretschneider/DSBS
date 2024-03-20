# DSBS – Daniel's Simple Backup Solution 
DSBS is a simple and leightweight application to backup certain local folders (Target Folder) on your PC recursively. 

# Where can I backup my local data?
At the moment there's the following possibilites:
* At a local path (f.e. on another partition)
* On a SMB-Drive (f.e. Windows File Server / Linux Samba Share)
* On a given network location

# Can I choose where each folder target is stored?
Yes, for every target you can choose the following options:
* Storage Type: local path, SMB, Network
* Update intervall: f.e. every 2 hours, after login, manual
* State: active / passive (targets in passiv state won't be backuped)

# Why C#?
Just for fun.

# Possible Features in Future:
* New Storage Types: Next Cloud, Web location, OneDrive, Dropbox
