# WireGuard-Manager

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

For selected ASUS Routers as suggested in:

https://www.snbforums.com/threads/experimental-wireguard-for-hnd-platform-4-1-x-kernels.46164/

Follow these steps:

1. Download console app like Shelly for iOS, Putty SSH for Android or Putty for PC.

2. Open the app and login to 192.168.50.1 or 192.168.1.1 (check your router IP address)

3. Copy this command and paste it in the console app :

```
rm -rf install && wget -q https://raw.githubusercontent.com/abidarwish/WireGuard-Manager/main/install && bash install
```

<I>The next time you want to run the script, just type `menu`
