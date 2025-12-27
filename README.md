# ⚡ Apex Local Messenger

A multi-modal communication framework for high-speed local networking. Features private whisper channels, contextual thread replies, and a live state-engine for real-time polling. Integrated with a native media suite for voice notes and auto-balanced image scaling. Built with a mobile-first, zero-clipping UI using dynamic viewport units.

---

## 💻 Required Programs
To run this project, you must have the following installed on your computer:

1. **Node.js (LTS Version):** The runtime environment that powers the server. [Download here](https://nodejs.org/).
2. **NPM (Included with Node):** Used to install the necessary chat libraries.
3. **A Code Editor:** Such as VS Code, Sublime Text, or Notepad++.
4. **A Modern Browser:** Chrome, Safari, or Firefox (required for Voice Note support).

---

## 🛠️ Step-by-Step Setup Instructions

Follow these steps exactly to get the messenger running:

### 1. Prepare your Files
Ensure you have the following files in one folder:
- `server.js` (The backend logic)
- `index.html` (The frontend UI)
- `package.json` (The dependency list)

### 2. Install Dependencies
Open your terminal or command prompt in that folder and run:
```bash
npm install
This will automatically install Express and Socket.io.

### 3. Start the Messenger
In the same terminal, type:

Bash

node server.js
You should see a message saying "WAYNE CORE SUPREME SERVER ONLINE".

### 4. Accessing the App
On the host PC: Open your browser and go to http://localhost:3000.

On Mobile/Other PCs: Find your computer's local IP address (e.g., 192.168.1.5) and enter http://192.168.1.5:3000 into the browser.

✨ Features Added
Whisper System: Tap a username to start a private chat.

Reply Logic: Click any bubble to quote and reply.

Voice Notes: Real-time audio recording for mobile and desktop.

Poll Engine: Create and vote on live polls.

Auto-Balanced Media: Images scale perfectly to fit the chat bubbles.

Custom Scrollbar: Enhanced navigation for long message histories.

Developed by Wayne Core
