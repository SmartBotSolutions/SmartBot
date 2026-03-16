<div align="center">

# 🤖 SmartBot

### Intelligent Game Automation for Android Emulators

**Automate your accounts. Maximize your progress. Play smarter.**



</div>

---

## What is SmartBot?

**SmartBot** is a powerful desktop automation tool for Windows that runs your mobile game accounts on Android emulators — 24/7, hands-free. It combines computer-vision-based automation with multi-account and multi-instance management, giving you a significant edge in time-gated strategy games.

Designed for players who want to progress efficiently without spending hours grinding manually, SmartBot handles the repetitive tasks so you can focus on strategy.

---

## 🎮 Supported Games

| Game | Package |
|------|---------|
| link | `link` |

> More games may be supported via custom `.bot` scripts.

---

## ✨ Key Features

### 🖱️ Visual Automation Engine
- Pixel-perfect click, swipe, and keyboard automation
- **Color/pixel detection** — triggers actions based on exact RGB values on screen
- **Image search** — finds and clicks UI elements by bitmap matching (powered by OpenCV)
- Randomized bounding boxes for human-like interaction patterns
- Millisecond-precision timing control

### 👥 Multi-Account Management
- Automatically rotates through multiple **Gmail / Google Play Games** accounts on the same emulator
- Per-account session isolation: clears Play Games cache between rotations
- Runs each account through the full game cycle without manual intervention

### 🖥️ Multi-Instance Support *(Premium)*
- Run the bot on **multiple emulator instances simultaneously**
- Supports **NoxPlayer** and **LDPlayer**
- Each instance runs its own independent script thread

### 🕐 Scheduler
- Set the bot to run on specific **days of the week** and **times**
- Configure repeat intervals in minutes
- View upcoming scheduled tasks and time remaining

### ♻️ Auto-Recovery (Watchdog)
- Detects unexpected game states or lost windows
- Automatically closes and relaunches the emulator to recover
- Keeps scripts running without human supervision

### 🧠 Scene Detection
- Hybrid fingerprinting engine (anchors + perceptual hashing)
- Identifies active game screens: loading, city, battle, menus
- Adapts bot behavior dynamically based on current game state

### 📦 AOZ Auto-Install
- One-click installation of Art of War: Legions (APK + OBB) on any emulator instance
- Automatic system patch injection for reliable bot control
- Supports installing and patching multiple emulator instances at once

### 🔄 Automatic Updates
- Checks GitHub on startup for new app versions and script updates
- Downloads and applies `.bot` script updates silently in the background

---

## 💼 Plans & Pricing

| Feature | Free | Premium |
|---------|------|---------|
| Daily usage | 2 hours/day | Unlimited |
| Emulator instances | 1 | Unlimited |
| Script event selector | Locked | Full access |
| Multi-account rotation | ✅ | ✅ |
| Scheduler | ❌ | ✅ |
| AOZ Auto-Install | 1 emulator | ✅ |
| Automatic updates | ✅ | ✅ |
| Priority support | ❌ | ✅ |
| License duration | - | 1 month (renewable) |

> **Premium licenses** are purchased via **Stripe** or **PayPal** and automatically activated — no manual key entry required. The license is tied to your device for security.

---

## 🌍 Available Languages

SmartBot is fully localized in **8 languages**:

🇺🇸 English &nbsp;|&nbsp; 🇪🇸 Español &nbsp;|&nbsp; 🇻🇳 Tiếng Việt &nbsp;|&nbsp; 🇩🇪 Deutsch &nbsp;|&nbsp; 🇫🇷 Français &nbsp;|&nbsp; 🇷🇺 Русский &nbsp;|&nbsp; 🇨🇳 中文 &nbsp;|&nbsp; 🇸🇦 العربية

---

## 🚀 Getting Started

### Requirements

- Windows 10 / 11 (64-bit)
- [NoxPlayer](https://www.bignox.com/) or [LDPlayer](https://www.ldplayer.net/) installed
- ADB enabled on your emulator

### Installation

1. Download the latest release from the [Releases page](../../releases)
2. Extract the `.zip` file to a folder of your choice
3. Run `SmartBot.exe`
4. SmartBot will check for updates automatically on first launch

### Setting Up AOZ

1. Open the **AOZ Install** tab
2. Select your emulator type (NoxPlayer / LDPlayer)
3. Choose the instances you want to set up
4. Click **Install + Patch** and wait for the process to complete

### Running Your First Script

1. Open the **Home** tab
2. Select a `.bot` script from the list
3. Choose your emulator instance
4. Click **▶ Play**

---

## 🔐 License Activation

### Automatic Activation (Recommended)
1. Purchase your Premium license via the Stripe or PayPal link in the app
2. After payment is confirmed, you will receive an activation code for SmartBot 
3. No copy-pasting keys required — activation is tied to your Machine ID

### Manual Activation
1. Go to **Settings → License**
2. Enter your license key and click **Activate**

---

## 🗂️ Application Overview

SmartBot's interface is organized into 5 sections:

| Section | Description |
|---------|-------------|
| **Home** | Select and launch scripts on any emulator instance |
| **Running Processes** | Monitor active scripts; pause, resume, restart, or stop them |
| **Scheduler** | Configure time-based automation tasks |
| **AOZ Install** | Install and patch Art of War: Legions on your emulators |
| **Settings** | Language selection, license management, update preferences |

---

## ❓ Frequently Asked Questions

**Q: Can I run multiple accounts at the same time?**  
A: Yes! With a Premium license, you can run SmartBot on multiple emulator instances simultaneously, each with its own script and account.

**Q: Does SmartBot work with accounts I already have?**  
A: Yes. SmartBot detects Gmail accounts already configured on your emulator and rotates through them automatically.

**Q: Is my license transferable to another PC?**  
A: Licenses are tied to your device's hardware ID. Contact support if you need to transfer to a new machine.

**Q: Will the bot keep running if the game crashes?**  
A: Yes. The built-in watchdog detects crashes or lost windows and automatically restarts the emulator and script.

**Q: How often are scripts updated?**  
A: SmartBot checks for script and app updates every time it launches. Updates are applied automatically in the background.

---

## ⚠️ Disclaimer

SmartBot is intended for personal use only. Users are responsible for complying with the Terms of Service of any game they automate. Use at your own discretion.

---

## 📞 Support

For help, bug reports, or feature requests, please open an [Issue](../../issues) or reach out via the community channels.

---

<div align="center">

**SmartBot** — *Because your time is better spent on strategy, not grinding.*

</div>
