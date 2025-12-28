# Lenovo ThinkPad T440s Hackintosh

<img width="1127" height="487" alt="image" src="https://github.com/user-attachments/assets/a84598ee-fc79-406d-8c34-4bcbf9bcf358" />

(i used MultimediaLucario Repository for the image)

OpenCore EFI configuration for **Lenovo ThinkPad T440s**, tested and used as a **daily driver**.

** When downloaded, create an EFI folder and paste BOOT and OC folders **

---

## 💻 Hardware Specs
- **CPU:** Intel Core i5-4300U
- **GPU:** Intel HD Graphics 4400
- **RAM:** 12 GB
- **WiFi:** Intel (Stock)
- **Ethernet:** Intel
- **Display Output:** Mini DisplayPort

---

## 🧠 Software
- **macOS:** Monterey
- **OpenCore:** 1.0.6

---

## ✅ What Works
- Graphics Acceleration (QE/CI)
- Audio
- Trackpad & TrackPoint
- Screen Brightness
- System Stability (usable as daily driver)
- Ethernet
- WiFi (via **HeliPort / itlwm**)
- Mini DisplayPort
- FN Keys:
  - Volume
  - Brightness
- Built-in Camera

---

## ❌ What Does Not Work
- Sleep (not fixed yet)
- Other FN Keys
- iServices out of the box  
  - Requires **manual SMBIOS / iServices patching**

---

## ⚠️ Important Notes
- This EFI is **NOT plug & play**
- **You MUST generate your own SMBIOS** before using it
- Do **NOT** reuse serial numbers
- WiFi works using **HeliPort**, since Intel cards are not natively supported by macOS

---

## 🤝 Contributions
If you know how to **fix sleep** on the ThinkPad T440s:
- Fork this repository
- Open a **Pull Request**
- It will be reviewed and accepted if it works ✅

---

## 📌 Disclaimer
This EFI is shared to help the community.  
Use it at your own risk and always understand what you are installing.

---
