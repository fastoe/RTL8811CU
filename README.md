# Realtek RTL8811CU Driver for Linux

Driver for 802.11ac USB adapter with RTL8811CU chipset.

### Build Status

| OS  | Build status |
| ------------- | ------------- |
| Ubuntu 22.04  | [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu_Debian.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions) |
| Ubuntu 20.04  | [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu_Debian.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions) |
| Kali Linux 2024.1  | [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu_Debian.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions) |
| LinuxMint 21.3 Cinnamon  | [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu_Debian.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions) |
| openSUSE Leap 15.5 | [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu_SUSE-Linux.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions) |

### A few known wireless cards that use this driver include:
* [Fastoe AC659 USB Wi-Fi Adapter](https://www.fastoe.com/p_ac650)

### Manual installation
For Ubuntu/Kali Linux/LinuxMint
```bash
sudo apt update
sudo apt-get -y install linux-headers-generic dkms git bc
git clone https://github.com/fastoe/RTL8811CU.git
cd RTL8811CU
make
sudo make install
sudo reboot
```

For openSUSE
```
sudo zypper update -y
sudo zypper install -y kernel-default-devel dkms git bc
git clone https://github.com/fastoe/RTL8811CU.git
cd RTL8811CU
make
sudo make install
sudo reboot
```

Enjoy!
