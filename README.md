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


# EVIL-EYE
### Kerangka Kerja Pengambilan Gambar Kamera Senyap

[![Version](https://img.shields.io/badge/version-0.1-red?style=flat-square)](https://github.com/RGSecurityTeam/evil-eye)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20macOS-blue?style=flat-square)](#)
[![Shell](https://img.shields.io/badge/shell-bash-orange?style=flat-square)](#)
[![PHP](https://img.shields.io/badge/php-7.4%2B-purple?style=flat-square)](#)

</div>

# Ringkasan 

- Sebuah kerangka kerja phishing kamera modular modern yang mampu secara diam-diam menangkap
gambar berkualitas tinggi
- dari webcam target menggunakan template rekayasa sosial
dan terowongan terenkripsi Cloudflare.

**Tools** Ini Hanya untuk keperluan `pendidikan` & `pengujian` penetrasi  ~*resmi*~.
</div>

---

## ⚠️ Disclaimer

> Alat ini dikembangkan khusus untuk tujuan pendidikan dan pengujian penetrasi yang diizinkan saja.
> Pengembang Evil-Eye tidak bertanggung jawab atas penyalahgunaan atau kerusakan apa pun yang disebabkan oleh program ini.
> Menggunakan alat ini terhadap individu atau sistem apa pun tanpa izin tertulis yang jelas adalah ilegal.
> Dengan menggunakan alat ini, Anda setuju bahwa Anda sepenuhnya bertanggung jawab atas tindakan Anda.

---

## ✨ Features

| Fitur | Keterangan |
|---|---|
| 📷 **Tangkapan Kamera Senyap** | Mengambil Gambar Dari Kamera Depan Target Melalui `getUserMedia` API Browser|
| 🌐 **Cloudflare Tunnel** | Langsung Menghasilkan Tautan HTTPS Publik — Tidak Perlu Penerusan Port |
| 🎭 **5 Templates Umpan** | YouTube Live, Birthday Wish, Secret Message, Fake Instagram, AI Chatbot |
| 📍 **Pencatan IP & UA** | Mencatat Alamat IP Korban - Agent Browser Saat Tautan Dibuka  |
| 🔧 **Installasi Dependensi Otomatis** | Mendeteksi Dan Menginstall Alat Yang Hilang Secara Otomatis Saat Pertama Kali Dijalankan |
| 🖥️ **Dukungan Lintas-Distro** | Kali Linux, Termux, Parrot OS, Ubuntu, macOS — Mendeteksi Sistem Operasi Dan Arsitektur Secara Otomatis |

---

## 📋 Persyaratan

### Sistem Operasi
- Kali Linux
- Parrot OS
- Ubuntu / Debian
- macOS (with Homebrew)
- Termux (Android)

  Untuk Operasi Sistem Termux,Pasang Aplikasi Termux Di Android Terlebih Dahulu!! Tetapi Untuk Aplikasi Termux Jangan Di Unduh Di Playstore Karena Bisa Menyebabkan Error

<h2 align="center">

Unduh Aplikasi Termux Nya Dibawah Ini:

👇👇
  
[![termux](https://img.shields.io/badge/termux-71-yellow.svg?style=flat)](https://sfile.co/eZK8yBBtOiv)


### Ketergantungan

| Alat | Tujuan | Installasi |
|---|---|---|
| `php` | Server Web Terintegrasi | *Auto-installed on first run*  |
| `curl` | Permintaan jaringan & Pemeriksaan Kesehatan | *Auto-installed on first run*  |
| `wget` | Unduh Biner Cloudflared | *Auto-installed on first run*  |
| `jq` | Pemprosesan JSON Untuk Template | *Auto-installed on first run*  |
| `cloudflared` | Tunnel HTTPS Publik | *Auto-downloaded on first run* |
| `lolcat` | Spanduk Terminal Berwarna-Warni | *Auto-installed on first run* |

---

## 🚀 Installasi

### 1. Clone the repository

```bash
git clone https://github.com/shopeebjm/evil-eye.git
```

### 2. Go to **evil-eye** Directory

```bash
cd evil-eye
```

### 3. Run

```bash
./evel.sh
```
- Jika Tidak Work!! Solusinya Adalah Sebelum Menggunakan Perintah `./evel.sh` Kalian Gunakan Perintah Ini Terlebih Dahulu `chmod +x evel.sh` !! Baru Gunakan Perintah `./evel.sh`.
Kalau Tidak Work Juga Langsung Aja Gunakan Perintah Ini `bash evel.sh`. Jadi `./evel.sh` Nya Tidak Usah Digunakan.

> `cloudflared` dan `lolcat` Akan Diinstall Secara Otomatis Jika Tidak DiTemukan.

---
## 🚀 Pengaturan Termux 
### Install ca-certificates
```bash
pkg update && pkg install ca-certificates -y
```
### update ca-certificates
```bash
export SSL_CERT_FILE=$PREFIX/etc/tls/cert.pem
```
> **install Dan Atur Ini `ca-certificates.` Jika Ini Tidak Di Aktifkan, the `cloudflare` Tunnel Tidak Akan dimulai.**

## 🎭 Templates

<details>
<summary><b>[01] YouTube Live TV</b></summary>

Menampilkan Halaman Siaran Langsung YouTube Palsu. Meminta Korban Untuk Mengizinkan Akses Kamera Untuk "Untuk Memverifikasi Usia Mereka" Atau "Mengaktifkan Mode Interaktif". Anda Memberikan Tautan Video YouTube Apapun Yang Diputar Tersemat Dihalaman Tersebut.

</details>

<details>
<summary><b>[02] Birthday Wish</b></summary>

Halaman Perayaan Ulang Tahun Yang Dipersonilisasi Dengan Animasi,Balon,Kue Dan Musik.Nama Korban Disematkan Dihalaman Tersebut.Izin Kamera Diminta Untuk "Mengmbil Photo Selfie Ulang Tahun".

</details>

<details>
<summary><b>[03] Secret Message</b></summary>

Sebuah Halaman Misterius Yang Mengklaim Memiliki Pesan Rahasia Untuk Target.Anda Menyediakan `.txt` file Berisi Konten Pesan Yang Dimuat Sebagai Sumber Data JSON.Akses Kamera Dipicu Di Latar Belakang.

</details>

<details>
<summary><b>[04] Fake Instagram Followers</b></summary>

Sebuah Halaman Palsu Yang Meyakinkan Menjanjikan Pengikut Instagram Gratis.Korban Diberitahu Bahwa Verifikasi Kamera Diperlukan Untuk "Membuktikan Bahwa Mereka Adalah Manusia ".

</details>

<details>
<summary><b>[05] AI Chatbot (Fake AI)</b></summary>

AntarMuka Obrolan Asisten AI Palsu.Akses Kamera Diminta Dilatar Belakang Saat Korban Berinteraksi Dengan Obrolan

</details>

---

### Dimana Data Yang Diambil Disimpan?

| Data | Lokasi |
|---|---|
| Gambar Kamera | `captured_imgs/cam<timestamp>.jpg` |
| Alamat IP | `captured_ip.txt` |

---

## 🌐 Telah Diuji Pada

| Sistem Operasi | Versi | Status |
|---|---|---|
| Kali Linux | 2024.x | ✅ Working |
| Termux | 0.118.x | ✅ Working |
| Parrot OS | 6.x | ✅ Working |
| Ubuntu | 22.04 / 24.04 | ✅ Working |
| macOS | Ventura / Sonoma | ✅ Working |

---

# Social Media

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

## Follow Me :

[![Messenger](https://img.shields.io/badge/Messengers-blue?style=for-the-badge&logo=messenger)](https://fb.me/shopee.bjm)
<a href="https://tiktok.com/@shopee.bjm"><img title="TikTok" src="https://img.shields.io/badge/-black?style=for-the-badge&logo=Tiktok"></a>
[![Instagram](https://img.shields.io/badge/Instagram-Follow-red?style=for-the-badge&logo=instagram)](https://instagram.com/shopee_banjarmasin)
[![Blog](https://img.shields.io/badge/Website-Visit-yellow?style=for-the-badge&logo=blogger)](https://kiplymacho.blogspot.com)
[![Facebook](https://img.shields.io/badge/Facebook-Like-red?style=for-the-badge&logo=facebook)](https://facebook.com/shopee.bjm)
[![HalamanFacebook](https://img.shields.io/badge/Halaman-Facebook-sky?style=for-the-badge&logo=facebook)](https://facebook.com/httpcustomkiplymacho)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-red?style=for-the-badge&logo=whatsapp)](https://wa.me/6285751032225)
[![Telegram](https://img.shields.io/badge/Forum-Diskusi-blue?style=for-the-badge&logo=forum)](https://t.me/shopeebjm)
<a href="https://youtube.com/@shopee_banjarmasin"><img title="YouTube" src="https://img.shields.io/badge/YouTube-@Shopee_Banjarmasin-red?style=for-the-badge&logo=Youtube"></a>
