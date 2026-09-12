# IP-Changer

![Bash](https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnu-bash)
![Tor](https://img.shields.io/badge/Network-Tor-7E4798?style=for-the-badge&logo=tor)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A lightweight and powerful Bash script that utilizes the Tor network to dynamically change your system's IP address at specified intervals. Perfect for security testing, automated scraping, and maintaining privacy during CLI operations.

## Features
- **Automated Rotation:** Automatically switch your IP address based on custom time intervals.
- **Infinite Mode:** Support for unlimited, continuous IP changes.
- **Easy Setup:** Simple installation via `git` or `curl`.
- **Root Protection:** Built-in checks to ensure network services are handled securely.

## Prerequisites
- A Linux-based OS
- `tor` and `curl` installed on your system
- Root (`sudo`) privileges




## Browser Configuration (Optional)
If you want to route your normal web browser traffic (like Firefox) through the rotating Tor IPs, you need to manually configure your browser's proxy settings.

Open your browser settings.

Search for Network Settings or Proxy.

Select Manual proxy configuration.

Set the SOCKS Host to 127.0.0.1 and Port to 9050.

Ensure SOCKS v5 is selected and save the changes.


<img width="1835" height="866" alt="Screenshot (455)" src="https://github.com/user-attachments/assets/2454a1bc-07e5-4fb3-8987-70a4f4e088c6" />


##  Installation

You can install `ip-changer` using either `git` or `curl`.

### Option 1: Using `git clone` (Recommended)
```shell
git clone https://github.com/harpind3r/ip-changer.git
cd ip-changer
chmod +x ip-changer.sh
bash ip-changer.sh

