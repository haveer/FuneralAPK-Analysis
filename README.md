# FuneralAPK-Analysis

⚠️ **WARNING**  
Do **NOT** run this APK on a real mobile device.  
Use emulators (e.g., Genymotion) or sandboxed environments only.

## 📄 Overview

This repository contains the reverse engineering and static/dynamic analysis of a suspicious APK disguised as a funeral notice app.

The APK appears to be developed by a **Chinese actor targeting Korean Android users**, and may contain functionality capable of:
- Wiping user data
- Damaging system files
- Establishing communication with a C2 server

## 🔍 Goals

- Extract and analyze code (DEX, smali, Java)
- Identify suspicious behaviors (file deletion, exec, su, Base64 decoding)
- Trace possible command-and-control (C2) infrastructure
- Share findings for educational purposes

## ⚙️ Tools Used

- jadx
- apktool
- strings
- Android Emulator (VirtualBox, Genymotion)
- Wireshark (network activity)
- frida (optional)
