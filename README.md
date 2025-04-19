# ✋ Gesture-Based Keyboard Input

## 🧾 Project Overview

This Python project allows users to control keyboard inputs using **hand gestures** detected from a webcam feed. It utilizes **MediaPipe** for hand tracking, **OpenCV** for camera input and visualization, and **PyAutoGUI** for simulating key presses based on finger count.

Raise 1 to 5 fingers to trigger different keyboard actions:
- 1 Finger → Right Arrow
- 2 Fingers → Left Arrow
- 3 Fingers → Up Arrow
- 4 Fingers → Down Arrow
- 5 Fingers → Spacebar

---

## 🚀 Key Features

- 🎥 Real-time hand tracking with a webcam
- 🤚 Finger counting using MediaPipe landmarks
- 🧠 Custom threshold logic for finger detection
- ⌨️ Keyboard control via PyAutoGUI
- 🧪 Built-in delay to prevent accidental repeat presses

---

## 🧰 Prerequisites

Install the following Python libraries before running:

```bash
pip install opencv-python mediapipe pyautogui
```

---

## 💻 Run the Application

Simply execute the script:

```bash
python your_script_name.py
```

> Make sure your webcam is enabled. A window will open showing your hand, and key presses will be triggered based on how many fingers are raised.

---

## ✋ Gesture-to-Key Mapping

| Fingers Shown | Key Pressed  |
|---------------|--------------|
| 1             | Right Arrow  |
| 2             | Left Arrow   |
| 3             | Up Arrow     |
| 4             | Down Arrow   |
| 5             | Spacebar     |

---

## 📁 Project Structure

```bash
hand-gesture-control/
├── 81b28c67-c77e-4d3f-b0ea-5fbf4776c159.py   # Main script
└── README.md                                 # Project documentation
```

---

## ⚙️ Customization

- 🧠 You can tweak the `count_fingers()` function to improve accuracy.
- ⏱ Change the `0.2` seconds delay to modify gesture responsiveness.
- 🎯 Modify gesture mappings by replacing `pyautogui.press()` keys.

---

## ⚠️ Known Issues

- Doesn't handle multiple hands (only tracks one).
- Detection might be less accurate in low light or complex backgrounds.
- Might trigger false positives due to fast hand movement.

---

## 🌱 Future Improvements

- Support for multiple gestures or custom gestures
- Voice feedback for triggered actions
- Configurable gesture-to-key mapping via UI or config file

---

## 🙏 Acknowledgments

- [MediaPipe](https://google.github.io/mediapipe/) by Google for hand landmark detection  
- [PyAutoGUI](https://pyautogui.readthedocs.io/) for automating keyboard input  
- [OpenCV](https://opencv.org/) for video processing

---

## 🙌 Author

Created by **Pankaj Prajapat**  
Follow me on [LinkedIn](www.linkedin.com/in/pankajprajapat367) | [GitHub]([https://github.com](https://github.com/Pankaj-Prajapat367))

