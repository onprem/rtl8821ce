## Realtek RTL8821CE Driver
The code in this repository is based on the [rtl8821ce driver in Endless OS's linux repository](https://github.com/endlessm/linux/tree/master/drivers/net/wireless/rtl8821ce), which in turn is based on https://github.com/alanfox2000/realtek-linux 

### Installation
#### Arch Linux
##### Installation from source
- Install dependencies using `sudo pacman -Syu linux-headers dkms`
- Clone the git repo and cd into it using `git clone https://github.com/prmsrswt/rtl8821ce && cd rtl8821ce`
- build and install the module using DKMS `sudo ./dkms-install.sh`

#### Ubuntu and Debian
```
sudo apt install bc module-assistant build-essential dkms
sudo m-a prepare
```