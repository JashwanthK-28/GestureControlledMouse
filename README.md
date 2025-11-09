# GestureControlledMouse  
A computer-vision-based system that allows users to control the mouse cursor and perform click/scroll and screenshot actions using hand gestures captured through a webcam.



# Overview  
GestureControlledMouse uses Python, OpenCV, and MediaPipe to track hand movements in real time and convert gestures into mouse actions such as cursor movement, click, screenshot and scroll.

This project demonstrates the integration of computer vision and human-computer interaction, making it an innovative and fun approach to controlling your system without touching the mouse.



# Installation  

## 1. Clone the repository  
```bash
git clone https://github.com/JashwanthK-28/GestureControlledMouse.git
cd GestureControlledMouse
````

### 2. Create (optional) virtual environment

```bash
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the main script:

```bash
python main.py
```

Then:

🖐 Bring your hand in front of the webcam
🖱 Move your hand → cursor moves
👆 Perform gestures → click/scroll actions

Press **Esc** or close the window to exit.

---

## 📁 Project Structure

```
GestureControlledMouse/
│
├── main.py             # Main execution script
├── utils.py            # Gesture logic & helper functions
├── requirements.txt    # List of dependencies
└── README.md           # Documentation
```

---

## 📦 Dependencies

* Python 3.x
* OpenCV
* MediaPipe
* PyAutoGUI
* Numpy

(These are installed automatically from requirements.txt)

---

## ⚠️ Limitations

* Requires good lighting conditions
* Background clutter may reduce accuracy
* May lag on low-end hardware
* Gesture detection accuracy depends on camera resolution

---

## 🚀 Future Improvements

* Multi-finger and custom gesture support
* Gesture recording and training
* GPU acceleration
* Multi-monitor support
* UI calibration tool

---

## 📄 License

This project is licensed under the **MIT License**.
Feel free to modify and use it.

---

## 📬 Contact

Created by **Jashwanth Kumar**
GitHub: [https://github.com/JashwanthK-28](https://github.com/JashwanthK-28)

If you'd like, I can also:
✅ Add badges
✅ Add GIF demo
✅ Auto-format sections
✅ Add step-by-step usage images

Just tell me!
