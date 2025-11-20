🎨 AI Virtual Drawing Application

A simple computer-vision-based drawing tool that allows users to draw in the air using their index finger, clear using the palm, and change colours using gestures. Built using Python, OpenCV, and MediaPipe.

🚀 Features

✏️ Draw using finger – The application tracks the index finger and draws on the screen.

✋ Clear using palm – Show your palm to clear the entire canvas.

🎨 Colour change – Switch drawing colours using simple hand gestures.

🫳 Stable tracking – Reduced jitter so the lines do not shake.

✌️ Multi-hand safety – App ignores extra hands and continues drawing smoothly.

🔧 Lightweight & beginner-friendly – Runs on a normal laptop webcam.

🛠 Tech Stack

Python

OpenCV

MediaPipe

📁 Project Structure
AI-virtual-drawing-application
│
├── main.py
├── utils.py
├── requirements.txt
└── README.md

▶️ How to Run
pip install -r requirements.txt
python main.py


Make sure your webcam is On.

📌 How It Works

The application detects the index finger tip using MediaPipe.

Tracks fingertip movement and draws lines on a white canvas.

Palm detection triggers the clear screen function.

Specific gestures change colour:

1 finger → Draw

2 fingers → Colour change

Palm → Clear

🖍 Gesture Controls
Gesture	Action
☝️ One Finger	Draw
✌️ Two Fingers	Change Colour
✋ Palm	Clear Screen
🧩 Future Improvements

Add eraser mode

Add thickness control

Save drawings

UI for selecting colours
