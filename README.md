# <img src="images/balena-etcher-electron.png" alt="Balena logo" height="70">balena-etcher-arm
## Balena Etcher untuk Raspberry Pi 4, PineBook Pro dan perangkat Arm lainnya
Built langsung dari sumber - https://github.com/balena-io/etcher
### [Build Instructions](etcher-build/README.md)
## Install memakai apt-get
### Repository paket - https://packagecloud.io/swift-arm/etcher
Cara menambah repository
```
curl -s https://packagecloud.io/install/repositories/swift-arm/etcher/script.deb.sh | sudo bash
```
Install balena Etcher
```
sudo apt-get install balena-etcher-electron
```

### Install secara manual
```
wget <deb package>
sudo apt install ./<deb package>
```
##
<b>Tested Devices</b>
- b860h android box - ubuntu dan debian
- hg680p android box - ubuntu dan debian
- Raspberry Pi 4 - Raspbian Buster
- PineBook Pro - Debian Stretch
- Asus Tinkerboard - Tinker OS (Debian Stretch)
##

<img src="images/etcher-flashing.png" alt="etcher flashing" height="500">

