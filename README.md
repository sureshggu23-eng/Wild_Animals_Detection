# Wild_Animals_Detection
# 🐅 AI-Based Wild Animal Detection and Alert System Using YOLOv8

## 📌 Project Description

The **AI-Based Wild Animal Detection and Alert System** is a computer vision project that uses Artificial Intelligence (AI) and Deep Learning to detect dangerous wild animals in real time through a webcam.

The system uses the YOLOv8 (You Only Look Once) object detection algorithm with a trained model to identify wild animals such as lions, tigers, leopards, cheetahs, and jaguars.

When a dangerous animal is detected with a confidence score greater than the specified threshold (50%), the system automatically triggers an audio alarm to alert nearby people. To prevent repeated alarms, the system includes a two-second alert interval.

The main objective of this project is to improve safety by providing an automated animal detection and alert mechanism that can be useful in wildlife monitoring, residential areas near forests, and other locations where wild animal encounters may occur.

## 🎯 Objectives

- Detect dangerous wild animals using real-time webcam input.
- Apply YOLOv8 for accurate and fast object detection.
- Identify specific wild animal classes.
- Generate automatic audio alerts when dangerous animals are detected.
- Reduce repeated alerts using a time-based alert mechanism.
- Improve safety through AI-powered wildlife monitoring.

## 🛠️ Technologies Used

- **Python** – Programming language.
- **YOLOv8** – Real-time object detection model.
- **OpenCV** – Webcam access and image processing.
- **PyTorch** – Deep learning framework.
- **Roboflow** – Dataset management.
- **Playsound** – Audio alarm playback.
- **NumPy** – Numerical operations.

## 🐾 Animals Detected

The system is configured to detect the following animals:

- Lion
- Tiger
- Leopard
- Cheetah
- Jaguar

## ⚙️ How It Works

1. The webcam captures real-time video frames.
2. Each frame is processed using the trained YOLOv8 model.
3. The model identifies objects and predicts their classes.
4. The system checks whether a detected animal belongs to the predefined dangerous animal classes.
5. If the detection confidence exceeds 50%, an audio alarm is triggered.
6. A two-second interval prevents continuous repeated alarm playback.
7. The detection process continues until the user presses the `Q` key.

## 📂 Project Structure

```text
Wild-Animal-Detection/
│
├── best (2).pt
│   └── Trained YOLOv8 model
│
├── suresh (2).ipynb
│   └── Project implementation
│
├── cyber-alarms-synthesized-116358.mp3
│   └── Audio alert sound
│
└── README.md
```

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Wild-Animal-Detection
```

### 2. Install Required Libraries

```bash
pip install ultralytics opencv-python numpy playsound roboflow
```

### 3. Configure the Project Files

Place the trained YOLOv8 model and alarm audio file in the project directory.

Update the model and audio file paths in the Python notebook according to your system.

### 4. Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells and allow webcam access.

Press `Q` to stop the detection process.

## 🌟 Applications

- Wildlife monitoring and protection.
- Forest boundary surveillance.
- Safety monitoring in villages near forests.
- Early warning systems for dangerous animal encounters.
- AI-based security and surveillance systems.

## 🔮 Future Enhancements

- Integrate IP cameras and CCTV surveillance.
- Send SMS and mobile notifications during animal detection.
- Develop a web-based monitoring dashboard.
- Add GPS-based animal location tracking.
- Deploy the system on Raspberry Pi or edge devices.
- Expand the detection model to support more animal species.

## 🏁 Conclusion

This project demonstrates how Artificial Intelligence and computer vision can be used to improve wildlife monitoring and human safety. By combining YOLOv8-based real-time animal detection with an automatic audio alert mechanism, the system provides a simple and effective approach to identifying potentially dangerous wild animals and notifying nearby people.

**Project Domain:** Artificial Intelligence | Machine Learning | Deep Learning | Computer Vision | Object Detection
