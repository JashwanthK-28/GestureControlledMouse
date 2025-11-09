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

## 2. Create (optional) virtual environment

```bash
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

## 3. Install dependencies

```bash
pip install -r requirements.txt
```


# Usage

Run the main script:

```bash
python main.py
```

Then:

 Bring your hand in front of the webcam
 Move your hand → cursor moves
 Perform gestures → click/scroll actions

Press **q** or close the window to exit.


## Project Structure

```
GestureControlledMouse/
│
├── main.py             
├── utils.py            
├── requirements.txt    
└── README.md           
```


# Dependencies

* Python 3.x
* OpenCV
* MediaPipe
* PyAutoGUI
* Numpy

