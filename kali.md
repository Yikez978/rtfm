# Kali Linux notes
Here are some of the things I typically do on a new installation of Kali Linux:

```
## Update packages. Do this before you're out in the field because it can take a while.
apt update && apt upgrade
apt autoremove

## If running as VMware guest:
apt install open-vm-tools-desktop

## If running as VirtualBox guest:
apt install virtualbox-guest-x11

## Install some of the tools I use:
apt install emacs shutter sshuttle
```

## Reverse direction of scroll wheel
```
gsettings set org.gnome.desktop.peripherals.mouse natural-scroll false
gsettings set org.gnome.desktop.peripherals.touchpad natural-scroll false
```
