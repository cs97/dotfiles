
# install doas and add user to wheel
```
apk add doas 
echo 'permit :wheel' > /etc/doas.d/doas.conf 
adduser USER_NAME wheel
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
apk add git htop podman
```

# cargo, rustlang
```
apk add rustup
```
```
rustup-init
```
```
source "$HOME/.cargo/env"
```
```
apk add build-base
```

# EFI
```
efibootmgr --create --disk /dev/sda --part 1 --label "Grub" --loader \\EFI\\alpine\\grubx64.efi 
```

# LAPCE
```
akp add lapce
```
### fix
```
DRI_PRIME=1 lapce ./files/
```
