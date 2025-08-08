# Quantd Linux ISO

Quantd Linux is a custom Debian-based live desktop distribution built with [Debian Live Build](https://wiki.debian.org/DebianLive).  
It uses the **MATE Desktop Environment**, **PipeWire** for audio, and includes **Bluetooth** support.  
This project builds a bootable ISO based on **Debian 12 (Bookworm)** for general desktop users.

---

## 🎯 Features

- ✅ Debian 12 (Stable) Base  
- ✅ Full MATE Desktop Environment  
- ✅ PipeWire as audio backend  
- ✅ Bluetooth support (BlueZ + Blueman)  
- ✅ LightDM as Display Manager  
- ✅ Network Manager, Firefox, VLC, GIMP, and more  

---
## 📷 Screenshots
![Quantd Linux Boot](https://i.postimg.cc/V67zCxkk/Screenshot-at-2025-08-08-12-03-37.png)
![Quantd Linux Desktop](https://i.postimg.cc/sgBGDJKW/Screenshot-at-2025-08-08-12-11-49.png)
![Quantd Linux Terminal](https://i.postimg.cc/Kz5Rspc6/Screenshot-at-2025-08-08-12-11-08.png)
![Quantd Linux System](https://i.postimg.cc/cCb1VVpb/Screenshot-at-2025-08-08-12-09-55.png)
## Download the ISO
### Latest
[20250807](https://archive.org/download/quantd-live-image-amd64.hybrid/quantd-live-image-amd64.hybrid.iso)  
### Archives
1. [20250805](https://archive.org/download/live-image-amd64.hybrid_202508/live-image-amd64.hybrid.iso)

## 🧪 Test the ISO

### Via QEMU:

```
qemu-system-x86_64 -cdrom live-image-amd64.hybrid.iso -m 2048
```

### Or write to USB:

```
sudo dd if=live-image-amd64.hybrid.iso of=/dev/sdX bs=4M status=progress
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
