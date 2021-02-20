# fwupd-commands
Commands for [fwupd](https://github.com/fwupd/fwupd).

Related:
- https://github.com/fwupd/fwupd#basic-usage-flow-command-line

## fwupd and fwupdmgr
```
sudo fwupdmgr --version
neofetch

fwupdmgr get-devices
sudo fwupdmgr get-devices
sudo fwupdmgr get-devices --show-all-devices

sudo fwupdmgr refresh --force

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

snap
```
sudo snap info fwupd

sudo snap install fwupd --classic
sudo snap refresh fwupd --classic

sudo snap install fwupd --channel=latest/stable --classic
sudo snap refresh fwupd --channel=latest/stable --classic

sudo snap install fwupd --channel=latest/candidate --classic
sudo snap refresh fwupd --channel=latest/candidate --classic

sudo snap install fwupd --channel=latest/edge --classic
sudo snap refresh fwupd --channel=latest/edge --classic

sudo snap remove fwupd
```

apt
```
sudo apt show fwupd

sudo apt-get install fwupd

sudo apt-get remove fwupd

sudo apt-get purge fwupd

sudo apt-get autoremove

```
