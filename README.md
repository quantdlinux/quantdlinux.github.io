# Quantd Linux ISO

Quantd Linux is a custom Debian-based live desktop distribution built with [Debian Live Build](https://wiki.debian.org/DebianLive).  
It uses the **MATE Desktop Environment**, **PipeWire** for audio, and includes **Bluetooth** support.  
This project builds a bootable ISO based on **Debian 13 (trixie)** for general desktop users.


---

## 🎯 Features

- ✅ Debian 13 (Stable) Base  
- ✅ Full MATE Desktop Environment  
- ✅ PipeWire as audio backend  
- ✅ Bluetooth support (BlueZ + Blueman)  
- ✅ LightDM as Display Manager  
- ✅ Network Manager, Firefox, VLC, GIMP, and more  

---
## 📷 Screenshots
![Quantd Linux Boot](https://i.postimg.cc/FzVkzW82/Screenshot-at-2025-08-16-23-39-06.png)
![Quantd Linux Desktop](https://i.postimg.cc/SK86vytm/Screenshot-at-2025-08-16-19-16-26.png)
![Quantd Linux Terminal](https://i.postimg.cc/wj25PxVY/Screenshot-at-2025-08-17-22-04-25.png)
![Quantd Linux System](https://i.postimg.cc/wTKkRGvZ/Screenshot-at-2025-08-17-22-04-53.png)
![Quantd Linux Installer](https://i.postimg.cc/GmfwkRyd/Screenshot-at-2025-08-17-21-56-06.png)
## Download the ISO
### Latest
[Release 2.0](https://archive.org/download/quantd-live-image-amd64.hybrid.0817.125/quantd-live-image-amd64.hybrid.0817.125.iso)
  
### Archives
* [Release 2.0](https://archive.org/download/quantd-live-image-amd64.hybrid.0817.125/quantd-live-image-amd64.hybrid.0817.125.iso)
* [Release 1.0](https://archive.org/download/quantd-live-image-amd64.hybrid/quantd-live-image-amd64.hybrid.iso)

### Write to USB:

```
sudo dd if=quantd-live-image-amd64.xxx.iso of=/dev/sdX bs=4M status=progress
```

Replace `/dev/sdX` with your USB device.

---
## References repositories
[https://github.com/quantdlinux/quantd-iso](https://github.com/quantdlinux/quantd-iso)
## 📜 License

GPLv3  
Education Purposes Only

---

## 🧩 Credits    

Based on [Debian Live Build](https://wiki.debian.org/DebianLive).  
MATE, PipeWire, Debian — all credits to the respective upstream developers.
