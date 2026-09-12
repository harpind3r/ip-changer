#  IP-Changer

![Bash](https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnu-bash)
![Tor](https://img.shields.io/badge/Network-Tor-7E4798?style=for-the-badge&logo=tor)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A lightweight and powerful Bash script that utilizes the Tor network to dynamically change your system's IP address at specified intervals. Perfect for security testing, automated scraping, and maintaining privacy during CLI operations.

##  Features
- **Automated Rotation:** Automatically switch your IP address based on custom time intervals.
- **Infinite Mode:** Support for unlimited, continuous IP changes.
- **Easy Setup:** Simple installation via `git` or `curl`.
- **Root Protection:** Built-in checks to ensure network services are handled securely.

## 🛠️ Prerequisites
- A Linux-based OS
- `tor` and `curl` installed on your system
- Root (`sudo`) privileges

##  Installation

You can install `ip-changer` using either `git` or `curl`.

### Option 1: Using `git clone` (Recommended)
```shell
git clone [https://github.com/harpind3r/ip-changer.git](https://github.com/harpind3r/ip-changer.git)
cd ip-changer
chmod +x ip-changer.sh
