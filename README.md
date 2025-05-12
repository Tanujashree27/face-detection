
# Real-Time Face Detection using OpenCV

This project demonstrates real-time face detection using OpenCV and a webcam. It utilizes Haar Cascade Classifier to detect human faces in video frames.

## 📸 Features

* Captures real-time video from the webcam
* Converts frames to grayscale for efficient processing
* Detects faces using Haarcascade classifier
* Displays a bounding box and count of detected faces
* Exits on pressing the `Esc` key

---

## 🧠 Technologies Used

* **C++**
* **OpenCV** (Modules: `imgproc`, `highgui`, `objdetect`, `videoio`)

---

## 🛠️ Prerequisites

* OpenCV installed on your system
* C++ compiler (e.g., `g++`)
* Webcam
* Haarcascade file: [`haarcascade_frontalface_default.xml`](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
  (Place this XML file in the same directory as the executable or provide the correct path.)

---

## 🚀 How to Run

### 1. Clone or download this repository

```bash
git clone https://github.com/your-username/face-detection-opencv.git
cd face-detection-opencv
```

### 2. Compile the code

```bash
g++ -o facedetect facedetect.cpp `pkg-config --cflags --libs opencv4`
```

### 3. Run the executable

```bash
./facedetect
```

Press `Esc` to exit the application.

---

## 📂 File Structure

```
.
├── facedetect.cpp
├── haarcascade_frontalface_default.xml
└── README.md
```

---

## 📝 Notes

* Ensure your webcam is not in use by other applications.
* Adjust detection parameters (like `scaleFactor`, `minNeighbors`, and `minSize`) for better results on different environments.

---

## 📸 Sample Output

> Rectangle around detected face(s) with a counter overlay in the top-left corner.

---
