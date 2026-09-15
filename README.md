# 🔥 Fire and Smoke Detection for Mining Safety

An **AI-powered UAV-based Fire and Smoke Detection System** designed for mining safety applications using the **YOLO object detection framework**.

The system analyzes images and video captured during UAV-based mining inspections and detects **fire and smoke** using bounding-box localization and confidence scores.

---

## 📌 Project Overview

Mining environments can contain significant fire-related risks. Early detection of fire and smoke can help improve safety and enable faster response to potential hazards.

This project uses **Deep Learning and Computer Vision** to automatically analyze UAV inspection footage and identify fire and smoke.

The system provides:

* 🔥 Fire detection
* 💨 Smoke detection
* 📦 Bounding-box localization
* 📊 Confidence scores
* 🖼️ Image-based detection
* 🎥 Video-based detection

---

## ✨ Features

* 🚁 UAV-based aerial image and video analysis
* 🔥 Detects fire
* 💨 Detects smoke
* 📦 Draws bounding boxes around detected objects
* 📊 Displays detection confidence scores
* 🖼️ Supports image analysis
* 🎥 Supports video analysis
* ⚡ Real-time object detection using YOLO

---

## 🏗️ System Workflow

```text
             UAV Aerial Image / Video
                       │
                       ▼
              ┌─────────────────┐
              │ Input Processing│
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │   YOLO Model    │
              └────────┬────────┘
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
          🔥 Fire             💨 Smoke
             │                   │
             └─────────┬─────────┘
                       ▼
              Bounding Box + 
             Confidence Score
                       │
                       ▼
               Detection Result
```

---

## 🤖 Object Detection

The project uses **YOLO (You Only Look Once)** for object detection.

For each detected object, the system provides:

```text
Object Class
     ↓
Fire / Smoke
     ↓
Bounding Box
     ↓
Confidence Score
```

Example:

```text
Fire
Confidence: 92%
```

The bounding box helps identify the exact region of the image or video frame where fire or smoke has been detected.

---

## 🖼️ Image Detection

The system can analyze UAV aerial images and identify fire and smoke present in the scene.

```text
UAV Image
   ↓
YOLO Detection
   ↓
Fire / Smoke Detection
   ↓
Bounding Box
   ↓
Confidence Score
```

This can assist in identifying potential fire hazards in mining areas from aerial imagery.

---

## 🎥 Video Detection

The system can also process UAV inspection videos frame by frame.

```text
UAV Video
    ↓
Video Frames
    ↓
YOLO Object Detection
    ↓
Fire / Smoke Detection
    ↓
Bounding Boxes
    ↓
Confidence Scores
```

Detected fire and smoke are displayed directly on the video frames using bounding boxes.

---

## 📂 Project Structure

```text
Fire-and-Smoke-Detection-for-Mining-Safety/
│
├── fire_smoke_model.py
├── fire_smoke_test.py
└── README.md
```

### File Description

| File                  | Description                                                           |
| --------------------- | --------------------------------------------------------------------- |
| `fire_smoke_model.py` | Contains the YOLO-based fire and smoke detection model implementation |
| `fire_smoke_test.py`  | Used for testing the fire and smoke detection system                  |
| `README.md`           | Project documentation                                                 |

---

## 🛠️ Technologies Used

* **Python**
* **YOLO**
* **Deep Learning**
* **Computer Vision**
* **Object Detection**

---

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/abdultouheed/Fire-and-Smoke-Detection-for-Mining-Safety.git
```

Navigate to the project:

```bash
cd Fire-and-Smoke-Detection-for-Mining-Safety
```

Run the model or testing script according to the implementation:

```bash
python fire_smoke_model.py
```

or

```bash
python fire_smoke_test.py
```

> Make sure the required Python dependencies and YOLO model files used by the project are available in your environment.

---

## 🎯 Applications

This system can be applied to:

* ⛏️ Mining safety monitoring
* 🚁 UAV-based mining inspection
* 🔥 Early fire detection
* 💨 Smoke detection
* 🏭 Industrial safety monitoring
* 🌲 Large-area hazard monitoring
* 📹 Automated inspection video analysis

---

## 📊 Detection Output

The system provides visual detection results containing:

Each detection includes:

* **Class:** Fire or Smoke
* **Confidence:** Model confidence score
* **Bounding Box:** Location of the detected object

---

## 🚀 Future Improvements

The system can be further improved by:

* Adding more diverse mining-environment training data
* Improving detection in low-light and high-smoke conditions
* Supporting real-time UAV camera feeds
* Adding automatic alerts when fire is detected
* Integrating GPS coordinates with detected hazards
* Developing a monitoring dashboard
* Recording detection events and timestamps
* Deploying the model on edge devices for UAV-based inference
* Improving detection accuracy with additional training data

---

## 👨‍💻 Author

**Abdul Touheed**

Computer Science Engineer | Machine Learning Enthusiast | Python Developer

---
