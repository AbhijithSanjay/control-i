# 👁️‍🗨️ Gaze-Controlled Virtual Keyboard

A submission for the **Vibe Coding Hackathon** by **TinkerHub**

This is a web-based virtual keyboard that allows users to type *without using their hands*, using just eye movement. With real-time eye tracking via a webcam, the user’s gaze is used to control a virtual cursor. Looking at a key for a short duration simulates a click — making this an innovative accessibility tool.

<img width="1812" height="880" alt="image" src="https://github.com/user-attachments/assets/68aff8a5-46a4-4885-ad7d-e6dc562842a6" />


---

## 🚀 Features

- **🎯 True Gaze Control**  
  Uses [WebGazer.js](https://webgazer.cs.brown.edu/) for real-time eye-tracking with your webcam.

- **🕒 Dwell-to-Click Typing**  
  Hover over a key with your gaze for ~1 second to simulate a keypress.

- **⌨️ Full QWERTY Layout**  
  Includes Shift, Space, Backspace, and Clear buttons for full functionality.

- **🎯 Manual Calibration System**  
  Recalibrate at any time to improve tracking accuracy.

- **🎥 Live Webcam Feedback**  
  Toggle your webcam preview to adjust your positioning.

- **📱 Responsive Design**  
  Built with Tailwind CSS to work seamlessly across screen sizes.

---

## 🛠️ Tech Stack

| Category     | Tools Used                      |
|--------------|----------------------------------|
| Frontend     | HTML5, CSS3, JavaScript (ES6+)   |
| Styling      | Tailwind CSS                    |
| Eye Tracking | WebGazer.js                     |

---

## ⚙️ Getting Started

> ⚠️ Browsers allow webcam access only on **HTTPS** sites or **localhost**.

### 🔧 Steps to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/gaze-keyboard.git
   cd gaze-keyboard
