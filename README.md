
---

```markdown
# 🔊 Volume Gesture Controller using Hand Tracking

This is a **Computer Vision project** that allows you to control your system volume using **hand gestures** in real-time via your webcam! It uses MediaPipe for hand tracking and OpenCV for image processing, along with the `pycaw` library to control system volume.



## 📁 Project Structure

- `HandTrackingModule.py` – This module handles hand detection, landmark drawing, and position finding using **MediaPipe**.
- `VolumeGesture.py` – This is the main script that captures hand gestures and adjusts system volume accordingly using **pycaw**.

## 🧠 How It Works

- The webcam captures your hand.
- The distance between your **thumb and index finger** is calculated.
- As the distance increases or decreases, the system volume changes accordingly.
- A volume bar and percentage are shown on the screen to reflect the changes.

## 📦 Libraries Used

- `OpenCV`
- `MediaPipe`
- `pycaw`
- `numpy`
- `math`

Install the required libraries using:

```bash
pip install opencv-python mediapipe pycaw numpy
```

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Moulik-23/Volume-Gesture-Project.git
cd Volume-Gesture-Project
```

2. Run the main script:

```bash
python VolumeGesture.py
```

Make sure your webcam is working and accessible.

## 🎯 Features

- Real-time hand tracking using webcam
- Smooth volume control using finger distance
- Visual feedback with volume bar and percentage
- Modular structure (easy to update and maintain)

## 🧠 Future Enhancements

- Add multi-hand support
- Integrate gesture-based mute/unmute
- Add UI for better user interaction

## 🧑‍💻 Author

**Moulik **  
Aspiring Data Scientist | Computer Vision Enthusiast  
[LinkedIn](www.linkedin.com/in/moulik-zinzala-2749752b7) • [Portfolio](https://portfolio-web-site-black.vercel.app/index.html) • [Email](mailto:moulikzinzala912@gmail.com)

---

Feel free to ⭐ the repo if you find it helpful!

```
