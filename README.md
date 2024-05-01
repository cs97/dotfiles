# dotfiles




### fedora sway
```
sudo dnf install git
```
```
sudo dnf install cargo
```
```
sudo dnf install mousepad
```

## snap
```
sudo dnf install snapd
```

```
sudo ln -s /var/lib/snapd/snap /snap
```
### rust editor
```
sudo snap install rustrover --edge --classic
```
```
sudo emerge --ask --verbose openjdk
```
### java editor
```
sudo snap install intellij-idea-community --classic
```



### sway status
```
git clone https://github.com/cs97/rusty-sway-status
```
```
cd rusty-sway-status/
```
```
cargo build --release --features battery-status
```
```
cp target/release/status /usr/bin/status
```


### Dark theme
```
dnf install arc-theme
```
```
gsettings set org.gnome.desktop.interface gtk-theme Arc-Dark
```
