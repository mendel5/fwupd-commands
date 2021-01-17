# fwupd-commands
Commands for [fwupd](https://github.com/fwupd/fwupd)

## fwupd and fwupdmgr
```
sudo fwupdmgr --version
neofetch

sudo fwupdmgr refresh --force

fwupdmgr get-devices
sudo fwupdmgr get-devices
sudo fwupdmgr get-devices --show-all-devices

sudo fwupdmgr get-updates

sudo fwupdmgr update

sudo fwupdmgr get-history

sudo fwupdmgr report-history
```

## installation

Links:
- https://github.com/fwupd/fwupd/releases
- https://github.com/fwupd/fwupd/wiki/fwupd-flatpak
- https://snapcraft.io/install/fwupd/mint

```
sudo snap install fwupd --classic

sudo snap info fwupd

sudo snap refresh fwupd

sudo snap remove fwupd

sudo apt-get remove fwupd

sudo apt-get purge fwupd

sudo apt-get autoremove

```
