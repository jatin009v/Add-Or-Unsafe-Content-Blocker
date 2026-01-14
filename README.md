🛡️ Smart Content Blocker
Focus on what matters. A powerful, zero-build Chrome extension that intelligently blocks inappropriate content and social media distractions using smart heuristic analysis.

https://raw.githubusercontent.com/jatin009v/Add-Or-Unsafe-Content-Blocker/main/images/meta.png

✨ Features
🧠 Smart Content Detection: Uses heuristic analysis to automatically identify and block inappropriate (adult/NSFW) content in real-time.

🚫 Social Media Blocker: One-click blocking for major distractions including Facebook, Instagram, Twitter/X, TikTok, and Reddit.

⚡ Zero-Build Required: No complex build tools needed. Works with standard HTML, CSS, and JavaScript.

🎨 Dynamic Block Page: Features an engaging, animated block page with GIFs from GIPHY API (with fallback emojis) to lighten the mood.

✅ Customizable Lists: Easily manage your allowed (whitelist) and blocked sites directly from the extension popup.

🔒 Privacy First: All analysis happens locally on your device. Your browsing data never leaves your computer.

🚀 Installation
Option 1: Load as Unpacked Extension (Developer Mode)
Download or Clone the Repository:
git clone https://github.com/jatin009v/Add-Or-Unsafe-Content-Blocker.git

Configure API Key (Optional, for GIF features):

Create a file named .env in the project root.

Add your GIPHY API key: GIPHY_API_KEY=your_key_here

Run npm run config to generate the configuration file.

Alternatively, manually create config.js in the root directory with:

export const CONFIG = {
  GIPHY_API_KEY: "your_key_here"
};

Load Extension in Chrome:

Open Chrome and navigate to chrome://extensions/

Enable Developer mode (toggle in top-right corner)

Click Load unpacked

Select the cloned repository folder

🛠️ Configuration
GIPHY API Setup (Optional)
For animated GIFs on the block page:

Visit GIPHY Developers Dashboard

Create an account and a new App

Copy your API Key

Add it to your .env file or directly into config.js

📖 How to Use
Extension Popup
Click the Smart Content Blocker icon in Chrome's toolbar to access:

Current Site Control: See the current domain and instantly add it to your Blocklist or Whitelist

Whitelist Management: Add trusted domains that should never be blocked

Quick Block: One-click buttons to block common social media platforms

Block Page Experience
When visiting a blocked site, you'll see:

A "Content Blocked" or "Stay Focused" message

A random focus-related GIF (if API is configured) or friendly emoji

Option to close the tab and return to productive work

💻 Technology Stack
Manifest V3: Built with latest Chrome Extension standards

Vanilla JavaScript: Lightweight, framework-free implementation

GSAP (GreenSock): Smooth, high-performance animations

Local Processing: All content analysis happens on-device for maximum privacy

🔧 Project Structure

smart-content-blocker/
├── manifest.json          # Extension configuration
├── popup.html            # Extension popup interface
├── popup.js              # Popup functionality
├── background.js         # Background service worker
├── content.js           # Content script for page analysis
├── block.html           # Block page interface
├── block.js             # Block page logic
├── styles.css           # Shared styles
├── images/              # Icons and assets
├── config.js            # API configuration (generated)
└── .env                 # Environment variables

🤝 Contributing
Contributions are welcome! Feel free to:

Fork the repository

Create a feature branch

Submit a Pull Request with detailed description

📝 License
This project is open source and available under the MIT License.

Stay focused, stay productive! ✨