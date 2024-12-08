
# install doas and add user to wheel
```
apk add doas 
echo 'permit :wheel' > /etc/doas.d/doas.conf 
adduser USER_NAME wheel 
su -l joe 
doas command with arguments
```

# setup Desktop (sway)
```
setup-desktop
```
```
apk add swaybg
```


# some tools
```
apk add cargo rust git htop podman
```


