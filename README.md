---

# 🛡️ DNS AdBlocker for Android

![adb](adb.png)

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Android-blue)
![Language](https://img.shields.io/badge/language-Python-yellow)
![Build](https://img.shields.io/badge/build-Gradle-orange)
![VPN](https://img.shields.io/badge/VPN-DNS%20Filter-red)
![Status](https://img.shields.io/badge/status-Active-success)

> A **powerful Python-based DNS ad blocker** running directly on Android using `VpnService`  
> 🚫 No root • 🔐 Encrypted DNS • ⚡ Real-time dashboard • 🧠 Fully customizable

---

## 🚀 Description (for GitHub repo)

A fully self-contained Android ad-blocking app built entirely in Python.  
It intercepts DNS traffic using Android's VPN API, filters malicious and ad domains, and forwards safe queries via encrypted DNS-over-HTTPS.

---

## 🎯 Features

- 🧠 **Advanced DNS filtering**
  - Exact match, wildcard, regex, subdomains

- 🔐 **Encrypted DNS (DoH)**
  - Uses Cloudflare or custom providers

- 🔄 **Auto-updating blocklists**
  - Supports public lists like StevenBlack

- 🧩 **Per-device rules**
  - Custom policies per IP

- ⚡ **High performance**
  - Async DNS server + caching

- 📊 **Live dashboard**
  - Flask + SocketIO real-time monitoring

- 💾 **Persistent logs**
  - SQLite storage

- 🔋 **Foreground service**
  - Always active in background

- 🐍 **Pure Python engine**
  - Embedded using Chaquopy

---

# ===============================
# 🚀 Build DNS AdBlocker APK
# ===============================

# 1️⃣ Clone repository
git clone https://github.com/yourusername/dns-adblocker-android.git
cd dns-adblocker-android

# 2️⃣ Configure Android SDK path
echo "sdk.dir=/home/youruser/android-sdk" > local.properties

# 3️⃣ Build debug APK
./gradlew assembleDebug

# ===============================
# 📦 Output APK
# ===============================
# app/build/outputs/apk/debug/app-debug.apk

📦 Output:

app/build/outputs/apk/debug/app-debug.apk


