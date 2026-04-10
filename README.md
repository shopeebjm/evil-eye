<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=YouTube+@shopee_banjarmasin" />
</p>
<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&lines=s+h+o+p+e+e+b+j+m" />
</p>

<p align='center'><a href="https://api.daily.dev/get?r=fisabiliyusri"><img src="https://raw.githubusercontent.com/fisabiliyusri/.github/main/kotori2.png?r=82s" width="150" alt="Hayuk"/></a></p>

<h2 align="center">
  
[![Powered By:shopeebjm](https://img.shields.io/badge/PoweredBy:shopeebjm-7%2B-blue.svg?style=flat)](http://linktr.ee/kiplymacho)

<div align="center">

<!-- Replace with your actual logo -->
<img src="/lib/imgs/evel-eye.png" alt="Evil-Eye Logo" width="160"/>

<br/>

# EVIL-EYE
### Silent Camera Capture Framework

[![Version](https://img.shields.io/badge/version-0.1-red?style=flat-square)](https://github.com/RGSecurityTeam/evil-eye)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20macOS-blue?style=flat-square)](#)
[![Shell](https://img.shields.io/badge/shell-bash-orange?style=flat-square)](#)
[![PHP](https://img.shields.io/badge/php-7.4%2B-purple?style=flat-square)](#)

<br/>

> A modern, modular camera phishing framework capable of silently capturing  
> high-quality images from a target's webcam using social engineering templates  
> and a Cloudflare encrypted tunnel.

<br/>

**Tools** Ini Hanya untuk keperluan `pendidikan` & `pengujian penetrasi` ~*resmi*~.

</div>

---

## ⚠️ Disclaimer

> Alat ini dikembangkan khusus untuk tujuan pendidikan dan pengujian penetrasi yang diizinkan saja.
> Pengembang Evil-Eye tidak bertanggung jawab atas penyalahgunaan atau kerusakan apa pun yang disebabkan oleh program ini.
> Menggunakan alat ini terhadap individu atau sistem apa pun tanpa izin tertulis yang jelas adalah ilegal.
> Dengan menggunakan alat ini, Anda setuju bahwa Anda sepenuhnya bertanggung jawab atas tindakan Anda.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📷 **Silent Camera Capture** | Captures images from the target's front camera via browser's `getUserMedia` API |
| 🌐 **Cloudflare Tunnel** | Instantly generates a public HTTPS link — no port forwarding needed |
| 🎭 **5 Lure Templates** | YouTube Live, Birthday Wish, Secret Message, Fake Instagram, AI Chatbot |
| 📍 **IP & UA Logging** | Logs victim's IP address and browser user-agent on link open |
| 🔧 **Auto Dependency Install** | Detects and installs missing tools automatically on first run |
| 🖥️ **Cross-Distro Support** | Kali Linux, Termux, Parrot OS, Ubuntu, macOS — auto-detects OS and architecture |

---

## 📋 Requirements

### Operating System
- Kali Linux
- Parrot OS
- Ubuntu / Debian
- macOS (with Homebrew)
- Termux (Android)

### Dependencies

| Tool | Purpose | Install |
|---|---|---|
| `php` | Built-in web server | *Auto-installed on first run*  |
| `curl` | Network requests & health checks | *Auto-installed on first run*  |
| `wget` | Download cloudflared binary | *Auto-installed on first run*  |
| `jq` | JSON processing for templates | *Auto-installed on first run*  |
| `cloudflared` | Public HTTPS tunnel | *Auto-downloaded on first run* |
| `lolcat` | Colorful terminal banners | *Auto-installed on first run* |

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/rgsecteam/evil-eye.git
```

### 2. Go to **evil-eye** Directory

```bash
cd evil-eye
```

### 3. Run

```bash
./evel.sh
```

> `cloudflared` and `lolcat` will be installed automatically if not found.

---
## 🚀 Termux Setup 
### Install ca-certificates
```bash
pkg update && pkg install ca-certificates -y
```
### update ca-certificates
```bash
export SSL_CERT_FILE=$PREFIX/etc/tls/cert.pem
```
> **install and setup this `ca-certificates.` If this is not enabled, the `cloudflare` tunnel will not start.**

## 🎭 Templates

<details>
<summary><b>[01] YouTube Live TV</b></summary>

Presents a fake YouTube Live stream page. Prompts the victim to allow camera access to "verify their age" or "enable interactive mode". You provide any YouTube video link which plays embedded on the page.

</details>

<details>
<summary><b>[02] Birthday Wish</b></summary>

A personalized birthday celebration page with animations, balloons, cake, and music. The victim's name is embedded in the page. Camera permission is requested to "take a birthday selfie".

</details>

<details>
<summary><b>[03] Secret Message</b></summary>

A mysterious page that claims to have a secret message for the target. You provide a `.txt` file with the message content which is loaded as a JSON data source. Camera access is triggered in the background.

</details>

<details>
<summary><b>[04] Fake Instagram Followers</b></summary>

A convincing fake page promising free Instagram followers. Victim is told camera verification is required to "prove they are human".

</details>

<details>
<summary><b>[05] AI Chatbot (Fake AI)</b></summary>

A fake AI assistant chat interface. Camera access is requested in the background while the victim interacts with the chat.

</details>

---

### Where is captured data saved?

| Data | Location |
|---|---|
| Camera images | `captured_imgs/cam<timestamp>.jpg` |
| IP addresses | `captured_ip.txt` |

---

## 🌐 Tested On

| OS | Version | Status |
|---|---|---|
| Kali Linux | 2024.x | ✅ Working |
| Termux | 0.118.x | ✅ Working |
| Parrot OS | 6.x | ✅ Working |
| Ubuntu | 22.04 / 24.04 | ✅ Working |
| macOS | Ventura / Sonoma | ✅ Working |

---

# Like Share Comment And Subscribe

<h2 align="center">

[![shopee](https://img.shields.io/badge/shopee-200%2B-yellow.svg?style=flat)](https://shopee.co.id/infinixnote40bjm)

[![Youtube shopee_banjarmasin](https://img.shields.io/badge/YouTube-200%2B-yellow.svg?style=flat)](https://www.youtube.com/@shopee_banjarmasin)

[![Instagram shopee_banjarmasn](https://img.shields.io/badge/Instagram-2K%2B-yellow.svg?style=flat)](https://www.instagram.com/shopee_banjarmasin)

[![Twitter KipyMacho](https://img.shields.io/badge/Twitter-350%2B-yellow.svg?style=flat)](https://www.twitter.com/kiplymacho)
  
[![Tiktok Shopeebjm](https://img.shields.io/badge/TikTok-80%2B-yellow.svg?style=flat)](https://www.tiktok.com/@shopee.bjm)

[![Facebook shopee.bjm](https://img.shields.io/badge/Facebook-199%2B-yellow.svg?style=flat)](https://www.facebook.com/shopee.bjm)

[![Telegram](https://img.shields.io/badge/Telegram-77%2B-yellow.svg?style=flat)](http://t.me/shopeebjm)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-80%2B-yellow.svg?style=flat)](http://www.linkedin.com/in/kiplymacho)

</p>
<div height='45' align="center">
<h2>Contact me: <br>
<a href="https://github.com/shopeebjm"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" height='50'> </a>
<a href="https://facebook.com/shopee.bjm"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" height='50'> </a>

<a href="https://paypal.me/kiplymacho"> <img src="https://cdn.trakteer.id/images/embed/trbtn-red-6.png" height='50'> </a>
</h2>
</div>
