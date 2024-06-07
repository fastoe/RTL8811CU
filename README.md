# Realtek RTL8811CU Driver for Linux

Build Status

Ubuntu 22.04: [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions)

Ubuntu 20.04: [![Build Status](https://github.com/fastoe/RTL8811CU/actions/workflows/rtl8811cu.yml/badge.svg)](https://github.com/fastoe/RTL8811CU/actions)

Driver for 802.11ac USB adapter with RTL8811CU chipset.

https://www.ebay.com/itm/395453935268

```bash
sudo apt update
sudo apt-get -y install linux-headers-generic dkms git bc
git clone https://github.com/fastoe/RTL8811CU.git
cd RTL8811CU
make
sudo make install
sudo reboot
```

Enjoy!
