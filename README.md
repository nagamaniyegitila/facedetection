👤 Real-Time Face Detection using OpenCV

«A Python-based computer vision project that detects human faces in real time using a webcam and OpenCV's Haar Cascade Classifier.»

---

📌 About the Project

Real-Time Face Detection is a simple computer vision application developed using Python and OpenCV.

The application uses the computer's webcam to capture live video. Each video frame is processed to identify human faces. When a face is detected, a rectangular bounding box is displayed around it.

If no face is visible in front of the camera, no detection box is displayed.

---

✨ Key Features

- 🎥 Real-time webcam video
- 👤 Automatic face detection
- 🔍 Haar Cascade Classifier
- ▫️ Face bounding boxes
- ⚡ Continuous frame processing
- 🚨 Camera availability checking
- ⌨️ ESC key to exit

---

🛠️ Technology Stack

Technology| Purpose
🐍 Python| Programming language
👁️ OpenCV| Computer vision and image processing
🔍 Haar Cascade| Face detection
📷 Webcam| Live video input
💻 VS Code| Development environment

---

🔄 Project Workflow

Webcam
   ↓
Capture Live Frame
   ↓
Convert to Grayscale
   ↓
Haar Cascade Detection
   ↓
Face Detected?
   ├── Yes → Draw Rectangle
   └── No  → Continue Detection
   ↓
Display Live Video
   ↓
ESC → Exit

---

🧠 How It Works

1️⃣ Webcam Initialization

The program connects to the computer's default webcam and starts capturing live video.

2️⃣ Frame Processing

Every frame received from the webcam is processed individually.

3️⃣ Grayscale Conversion

The captured frame is converted into grayscale to prepare it for face detection.

4️⃣ Face Detection

OpenCV's pre-trained:

"haarcascade_frontalface_default.xml"

classifier is used to detect faces.

5️⃣ Face Highlighting

When a face is detected, a rectangular box is drawn around it.

6️⃣ Real-Time Display

The processed frames are continuously displayed in the Face Detection window.

7️⃣ Exit

Press ESC to stop the application and release the webcam.

---

📋 Requirements

Before running the project, make sure you have:

- Python installed
- A working webcam
- Visual Studio Code
- OpenCV Python package

---

📦 Installation

Install OpenCV using the VS Code terminal:

pip install opencv-python

---

🚀 Run the Project

Step 1 — Open the project

Open the project folder in VS Code.

Step 2 — Create the Python file

face_detection.py

Step 3 — Add the code

Paste the face detection program into the Python file.

Step 4 — Run the program

python face_detection.py

Step 5 — Allow camera access

Allow webcam access if your system asks for permission.

Step 6 — Test the application

Stand in front of the webcam.

Face visible → Face is detected and a rectangle appears.

Face not visible → No rectangle is displayed.

Step 7 — Exit

Press ESC to close the application.

---

📂 Project Structure

Face-Detection/
│
├── face_detection.py
│
└── README.md

---

🎯 Learning Outcomes

By developing this project, the following concepts are demonstrated:

- Python programming
- Computer Vision fundamentals
- OpenCV
- Image processing
- Real-time video capture
- Grayscale conversion
- Haar Cascade Classifier
- Face detection
- Webcam integration

---

🔮 Future Improvements

Possible enhancements include:

- 👥 Face counting
- 🧑‍💼 Face recognition
- 📋 Face-based attendance system
- 🎯 Face tracking
- 📊 Detection confidence display
- 🤖 More advanced face detection models

---

👨‍💻 Author

Naga Mani Yegitila

---

⭐ Project

If you find this project useful, feel free to give the repository a star ⭐.
