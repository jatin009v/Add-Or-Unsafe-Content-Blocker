# 🛡️ Add-Or-Unsafe-Content-Blocker

> **Focus on what matters.**  
> A powerful, zero-build Chrome extension that intelligently blocks inappropriate content and social media distractions using smart heuristic analysis — all while keeping your data private.

![Smart Content Blocker](images/meta.jpg)

## ✨ Features

- **🧠 Smart Content Detection**  
  Uses local heuristic-based analysis to automatically detect and block inappropriate (adult/NSFW) content in real-time.

- **🚫 Social Media Blocker**  
  Pre-configured blocking for major distractions such as Facebook, Instagram, Twitter/X, TikTok, and Reddit.

- **⚡ Zero-Build Architecture**  
  No Webpack, no Parcel, no heavy tooling. Built using plain HTML, CSS, and JavaScript.

- **🎨 Dynamic Block Page**  
  A clean, animated block page that displays motivational GIFs using the GIPHY API, with emoji fallback support.

- **✅ Whitelist & Blocklist Management**  
  Easily allow or block websites directly from the extension popup interface.

- **🔒 Privacy First**  
  All content analysis runs locally on your device. No browsing history or personal data is sent anywhere.

## 🚀 Installation

### Option 1: Load Unpacked Extension (Developer Mode)

1. **Clone the repository**
   ```bash
   git clone https://github.com/jatin009v/Add-Or-Unsafe-Content-Blocker.git
   ```

   (Optional) Configure GIPHY API

   Create a .env file in the project root

   Add your API key:
   GIPHY_API_KEY=your_key_here

   Run:
   npm run config


   OR manually create config.js:

   export const CONFIG = {
     GIPHY_API_KEY: "your_key_here"
   };


   Load the extension in Chrome

   Open chrome://extensions/

   Enable Developer mode

   Click Load unpacked

   Select the project folder

   ✅ Extension is now active.

📖 Usage

🔘 Extension Popup

Click the Smart Content Blocker icon to:

View the current website
Instantly add it to the Blocklist or Whitelist
Quickly block popular social media platforms

🚫 Block Page

When accessing a blocked website:

A “Content Blocked” / “Stay Focused” message is displayed
A random motivational GIF or friendly emoji appears
Use Close Tab to immediately return to productive work

💻 Technologies Used

Manifest V3 – Latest Chrome extension standard

Vanilla JavaScript – Lightweight and fast

GSAP (GreenSock) – Smooth animations

Local Heuristic Analysis – On-device content filtering

🧑‍💻 Author

Made with ❤️ by Jatin

Stay focused. Stay productive.
