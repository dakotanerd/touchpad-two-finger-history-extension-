# touchpad-two-finger-history

A Firefox extension that enables **two-finger touchpad swipe navigation** for browser history, similar to native gestures on modern operating systems.

---

## ✨ Features

- 🖐️ Two-finger swipe left → Go back in history  
- 🖐️ Two-finger swipe right → Go forward in history  
- 🎯 Gesture-based navigation using touchpad scroll input  
- ➡️ Visual arrow indicator that appears during swipes  
- ⚡ Smooth and responsive interactions  
- 🔒 Prevents accidental repeated triggers with gesture locking and cooldown handling  
- 🚀 Instant navigation for a snappy user experience  

---

## 🎥 How it works

The extension listens for touchpad **wheel (scroll) events** and interprets horizontal movement as a gesture. When the swipe distance exceeds a defined threshold, it triggers a navigation action:

- Horizontal movement is accumulated during a gesture  
- A threshold determines when navigation occurs  
- Only one navigation is allowed per gesture  
- A cooldown system prevents repeated triggers  
- A visual arrow provides feedback during the swipe  

---

## 📦 Installation

### Option 1: Load temporarily in Firefox

1. Open Firefox
2. Navigate to:  about:debugging#/runtime/this-firefox
3. Click **"Load Temporary Add-on"**
4. Select the extension’s `manifest.json` file

---

### Option 2: Build and load

1. Clone the repository:
```bash
git clone https://github.com/your-username/touchpad-two-finger-history.git
