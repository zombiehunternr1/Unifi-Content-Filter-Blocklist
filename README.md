# Unifi Ultimate Blocklist

This repository provides a **comprehensive blocklist** for the **Content Filter** option in **Unifi**.  
It is designed to block most, if not all, recently known **ads, malware, trackers, spyware, and pirate sites**.

## Available Versions

To cater to different user needs, two versions of the blocklist are available:

### 1. With Torrent Sites Blocked

- **Filename:** [`Blocklist with torrent sites.txt`](./Blocklist%20with%20torrent%20sites.txt)  
- **Description:** This version includes entries that block access to known torrent and file-sharing sites. Ideal for environments where such services should be restricted.

### 2. Without Torrent Sites Blocked

- **Filename:** [`Blocklist without torrent sites.txt`](./Blocklist%20without%20torrent%20sites.txt)  
- **Description:** This version excludes entries related to torrent and file-sharing sites. Suitable for networks where such services are permitted.


**Download and upload** directly into the Unifi Controller under the Content Filter Blocklist, or  
**Copy-paste the raw contents** into the Content Filter Blocklist field in your Unifi settings.

---

## ✅ Testing & Verification

To ensure the blocklist works as intended, it has been tested with the following tools across **Edge** and **Chrome** browsers:

- [Turtlecute Adblock Test](https://adblock.turtlecute.org/)  
- [Super Adblock Test](https://superadblocktest.com/)  
- [Ad Blocker Test](https://paileactivist.github.io/toolz/adblock.html)  
- [Network Protection Tester](https://itproexpert.com/network-protection-tester/)

---

## 📸 Test Results

### Turtlecute Adblock Test
![Turtlecute Test](Screenshots/TurtecuteAdblockTest.jpg)

### Super Adblock Test
![Super Adblock Test](Screenshots/SuperAdblockTest.jpeg)

### Ad Blocker Test
![Ad Blocker Test](Screenshots/AdBlockerTest.jpeg)

### Network Protection Tester
![Network Protection Test](Screenshots/NetworkProtectionTester.jpeg)

---

## 📥 How to Use

1. Download [`Unifi ultimate blocklist.txt`](./Unifi%20ultimate%20blocklist.txt).  
2. Go to your **Unifi Controller** → **Settings** → **CyberSecure** → **Content Filter**.  
3. Click on **Create New**.
4. In the section **Blocklist** ether:
   - Add the domains one by one manually
   - Click on **Add Multiple** and upload the `.txt` file, **or**
   - Click on **Add Multiple** and copy the raw text and paste it into the **Blocklist** field.  
6. Click on **Add**.

---

## 🛡️ Features

- Blocks **ads** across the majority of known networks.  
- Protects against **malware, trackers and spyware** domains.  
- Prevents access to **pirate and illegal streaming sites**.  
- Works seamlessly with Unifi’s **built-in Content Filter**.

---

## ⚠️ Disclaimer

This blocklist is provided **as-is**. While it blocks a wide range of unwanted domains, false positives may occur.  
Use at your own discretion and adjust the blocklist according to your network needs.
