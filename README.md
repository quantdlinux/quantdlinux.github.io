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
![Quantd Linux Boot](https://i.postimg.cc/bw40gGg6/Screenshot-at-2025-08-16-19-15-46.png)
![Quantd Linux Desktop](https://i.postimg.cc/SK86vytm/Screenshot-at-2025-08-16-19-16-26.png)
![Quantd Linux Terminal](https://i.postimg.cc/Y02Q0Q2S/Screenshot-at-2025-08-16-19-25-53.png)
![Quantd Linux System](https://i.postimg.cc/rmk16vvx/Screenshot-at-2025-08-16-19-26-32.png)
![Quantd Linux Desktop2](https://i.postimg.cc/fLfxM8NF/Screenshot-at-2025-08-16-19-27-24.png)
## Download the ISO
### Latest
[Release 2.0](https://mega.nz/file/LOpCmAoQ#AYTKuvjWAMAPTIWWPCbhN0jcD3hhkxophx1vtxFOQb4)
  
### Archives
* [Release 1.0](https://archive.org/download/quantd-live-image-amd64.hybrid/quantd-live-image-amd64.hybrid.iso)
* [20250805](https://archive.org/download/live-image-amd64.hybrid_202508/live-image-amd64.hybrid.iso)

### Write to USB:

```
sudo dd if= quantd-image-amd64.hybrid.v2.0 .iso of=/dev/sdX bs=4M status=progress
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
