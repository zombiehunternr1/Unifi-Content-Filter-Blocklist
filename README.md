# Unifi Ultimate Blocklist

This repository provides a **comprehensive blocklist** for the **Content Filter** option in **Unifi**.  
It is designed to block most, if not all, recently known **ads, malware, trackers, spyware, and pirate sites**.

---

## Available Versions

To cater to different user needs, two versions of the blocklist are available:

### 1. With Torrent Sites Blocked

- **Filename:** [`Blocklist with torrent sites.txt`](./Blocklist%20with%20torrent%20sites.txt)  
- **Description:** This version includes entries that block access to known torrent and file-sharing sites. Ideal for environments where such services should be restricted.

### 2. Without Torrent Sites Blocked

- **Filename:** [`Blocklist without torrent sites.txt`](./Blocklist%20without%20torrent%20sites.txt)  
- **Description:** This version excludes entries related to torrent and file-sharing sites. Suitable for networks where such services are permitted.

---

## 📥 How to Use

1. Download the desired blocklist file mentioned above.
2. Go to your **Unifi Controller** → **Settings** → **CyberSecure** → **Content Filter**.  
3. Click **Create New**.  
4. In the **Blocklist** section, either:
   - Add the domains manually, or  
   - Click **Add Multiple** and **upload the `.txt` file**, or  
   - Click **Add Multiple** and **copy-paste the raw text** into the field.  
5. Click **Add** to save.

---

## 🛡️ Features

- Blocks **ads** across the majority of known networks.  
- Protects against **malware, trackers, and spyware** domains.  
- Prevents access to **pirate and illegal streaming sites**.  
- Works seamlessly with Unifi’s **built-in Content Filter**.

---

## ✅ Testing & Verification

The blocklist has been tested with the following tools across **Edge** and **Chrome** browsers:

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

## ⚠️ Disclaimer

These blocklists are provided **as-is**. While they blocks a wide range of unwanted domains, false positives may occur.  
Use at your own discretion and adjust the blocklist you choose according to your network needs.
