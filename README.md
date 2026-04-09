# Supermium-FOR-ARM32-chrome77-

> **Warning:** This is an **unstable, experimental** port of the Chromium browser targeting Windows RT and other `aarch32` platforms. Expect bugs, crashes, and missing features. Use at your own risk.

---

## 📋 Overview

This project provides an unofficial build of Chromium for devices running **Windows RT** and other **ARM 32-bit (aarch32)** operating systems, such as:

- Nokia Lumia devices (e.g. Lumia 1320, 920, 1020)
- Microsoft Surface RT / Surface 2
- Other WOA (Windows on ARM) aarch32 devices

Modern Chromium has dropped official support for 32-bit ARM Windows. This project attempts to bring a functional browser to these otherwise unsupported platforms.

---

## 🚧 Status

| Feature | Status |
|---|---|
| Basic browsing | ⚠️ Partially working |
| JavaScript | ⚠️ Unstable |
| Hardware acceleration | ❌ Not supported |
| Extensions | ❌ Not supported |
| Video playback | ❌ Not supported |
| Touchscreen input | Working💚 |

---

## 📦 Requirements

- Windows RT 8.1 or compatible aarch32 Windows OS
- Device with ARMv7 / aarch32 CPU
- At least **1 GB RAM** recommended
- Jailbroken / sideload-enabled device (for unsigned binary execution)

---

## ⚙️ Installation

1. Download the latest unstable release from the [Releases](#) page.
2. Extract the archive to a folder on your device.
3. Run `chrome.exe` directly — no installer required.

> **Note:** Because this build is unsigned, you may need to enable developer/sideload mode on your device or use a workaround for driver signature enforcement.

---

## 🐛 Known Issues

- Frequent crashes on JavaScript-heavy websites
- No GPU acceleration — rendering is CPU-only (slow)
- Some pages may fail to load or display incorrectly
- Audio may not work on all devices
- Memory usage is high compared to other aarch32 browsers

---

## 🔗 Related Projects

- [WOA-Project / Windows on ARM](https://github.com/WOA-Project) — Windows on ARM for Lumia devices
- [XDA Developers — Windows RT thread](https://forum.xda-developers.com) — Community discussion

---

## ⚠️ Disclaimer

This is an **unofficial, community-made port**. It is not affiliated with Google or the Chromium project. No warranty is provided. This software may be unstable and could cause unexpected behavior on your device.

---

## 🤝 Contributing

PRs and issue reports are welcome! If you have a compatible device and want to help test or improve this port, feel free to open an issue or contribute to the build scripts.

---

*Built with ❤️ for forgotten ARM devices.*
