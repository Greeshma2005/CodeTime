# CodeTime ⏱️

**CodeTime** is a lightweight Chrome extension that automatically tracks your coding time across popular developer platforms. It helps you visualize your daily habits, maintain consistency, and stay motivated with a clean and minimal interface.

---

## 🔧 Features

- ⏲️ **Auto Time Tracking** across sites like LeetCode, GitHub, and Codeforces
- 📈 **Daily, Weekly, Monthly Views** with visual breakdowns
- 🔥 **Streak Tracker** to help you build habits
- 📊 **Charts** using Chart.js for beautiful analytics
- 🌐 **Multi-platform Support**
- 🌙 **Dark Theme** with responsive design
- 🧠 **100% Offline & Private** (no data leaves your browser)

---

## 🌐 Supported Platforms

- LeetCode
- GitHub
- Codeforces
- GeeksforGeeks
- HackerRank
- CodeChef

---

## 🖥️ Installation

1. Download CodeTime from GitHub:
   - Visit: [https://github.com/Greeshma2005/CodeTime](https://github.com/Greeshma2005/CodeTime)
   - Click “Code” → “Download ZIP” and extract it

2. Load into Chrome:
   - Open `chrome://extensions/`
   - Enable **Developer mode**
   - Click **Load unpacked**
   - Select the extracted `CodeTime` folder

3. You're done! Start visiting coding sites and click the extension icon to see your stats.

---

## 📊 How It Works

- A background service worker detects which coding site you're on
- Time is tracked per site and saved locally
- When you open the popup, you'll see:
  - Today’s total time + breakdown
  - Weekly and monthly charts
  - Your current coding streak

Built using `manifest v3`, JavaScript, and `Chart.js`.

---

## 🗃️ File Structure

CodeTime/
├── manifest.json          # Extension configuration  
├── background.js          # Service worker for time tracking  
├── popup.html             # Extension popup interface  
├── popup.js               # Popup functionality and charts  
├── popup.css              # Styling for the popup  
├── chart.min.js           # Chart.js library  
└── icons/                 # Extension icons  
    ├── icon16.png  
    ├── icon32.png  
    ├── icon48.png  
    └── icon128.png  



---

## 🛠 Development & Contributions

Interested in improving CodeTime?

1. Fork this repo
2. Create a feature branch
3. Make your changes and push
4. Open a pull request

Ideas to contribute:
- Add support for more platforms
- Add time export/download feature
- Add goal-setting or reminders
- Build a desktop dashboard

---

## 🛡️ Privacy First

- No server or cloud usage
- All stats are stored using Chrome’s local storage
- Works completely offline
- No personal data is ever collected

---

## ❓ Need Help?

Open an issue or drop feedback here:  
🔗 [https://github.com/Greeshma2005/CodeTime/issues](https://github.com/Greeshma2005/CodeTime/issues)

---

**Built with 💻 and ☕ to fuel your coding journey with CodeTime.**

**Stay consistent. Track your progress. Code smarter. 🚀**

