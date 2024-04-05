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


### sway status
```
git clone https://github.com/cs97/rusty-sway-status
cd rusty-sway-status/
cargo build --release --features battery-status
cp target/release/status /usr/bin/status
```


### Dark theme
```
dnf install arc-theme
```
```
gsettings set org.gnome.desktop.interface gtk-theme Arc-Dark
```
