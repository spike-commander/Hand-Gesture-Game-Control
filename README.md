# Hand-Gesture-Game-Control
A real-time computer vision project that uses hand gesture recognition via webcam to automate gameplay actions in game Subway Surfers.  This system detects hand landmarks using MediaPipe and converts gestures into keyboard commands using PyAutoGUI, enabling hands-free gaming interaction.
## 🚀 Key Highlights

- Real-time hand tracking with MediaPipe
- Gesture-based keyboard automation
- Directional movement detection
- Action cooldown to prevent repeated inputs
- Webcam gameplay recording
- Lightweight and runs on CPU

---

## 🧠 Tech Stack

| Category | Tools Used |
|---------|------------|
| Language | Python |
| Computer Vision | OpenCV |
| Hand Tracking | MediaPipe |
| Automation | PyAutoGUI |
| Numerical Processing | NumPy |

---

## ⚙️ System Architecture

1. Capture live webcam feed using OpenCV
2. Detect hand landmarks using MediaPipe
3. Analyze finger positions and movement direction
4. Map gestures to keyboard inputs
5. Execute game actions via PyAutoGUI

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/hand-gesture-game-control.git
cd hand-gesture-game-control
````

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

```bash
python gestureControl.py
```

### Before Running

* Open the game (Subway Surfers or emulator)
* Ensure webcam is connected
* Maintain proper lighting
* Keep hand clearly visible

---

## 📁 Project Structure

```
hand-gesture-game-control/
│
├── gestureControl.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🎥 Output

* Detects hand gestures in real-time
* Automates keyboard actions
* Saves webcam output recording:

```
gesture_recording.mp4
```

---

## ⚠️ Known Limitations

* Optimized for single-hand usage
* Requires stable lighting conditions
* CPU intensive on low-end machines

---

## 🔮 Future Enhancements

* Deep learning gesture classification
* GUI dashboard
* Multi-hand gesture recognition
* FPS optimization
* Custom gesture training system

---

## 🤝 Contributions

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Submit pull request

---

## 👨‍💻 Author

ABDUL HAIY
GitHub: [https://github.com/yourusername](https://github.com/spike-commander)
