WARNING:

has dangling X sessions andwill eventually have to remove them:


cd /tmp/.X11-unix

sudo rm /tmp/.X11-unix/X*


cd /tmp

rm /tmp/.X*-lock


#how to free disk space
```
wsl --shutdown
diskpart
# open window Diskpart
```

```
select vdisk file="C:\WSL-Distros\…\ext4.vhdx"
attach vdisk readonly
compact vdisk
detach vdisk
exit
```
