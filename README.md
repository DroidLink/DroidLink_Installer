# DroidLink Web Installer

This repository contains the official DroidLink web-based installer used to flash firmware onto supported DroidLink devices via a modern web browser.

It provides a simple, guided installation experience and does not contain firmware source code.

---

## What This Installer Does

- Installs DroidLink firmware using Web Serial
- Works in supported browsers (Chrome / Edge)
- Supports installation for:
  - Master Controller
  - Universal Slave
  - Display Module
- Requires no local IDE, toolchain, or drivers

---

## What This Repository Does NOT Include

- Firmware source code
- Firmware binaries
- License key validation logic
- OTA update logic

Firmware binaries are distributed separately to licensed users.

---

## Usage

End users should access the installer through the official page:

👉 https://droidlink.github.io/DroidLink_Installer/

No interaction with this repository is required for normal use.

---

## Full Documentation

For setup guides, hardware documentation, command reference, and system architecture:

👉 https://github.com/DroidLink/DroidLink_Docs

---

## Supported Browsers

- Google Chrome (recommended)
- Microsoft Edge

Other browsers may not support Web Serial.

---

## License

The contents of this repository are licensed under the MIT License.

This license applies **only** to the web installer code contained in this repository.  
DroidLink firmware and product usage are licensed separately.

---

## Disclaimer

This installer is provided "as is", without warranty of any kind.
