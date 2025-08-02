# 🧥 Invisibility Cloak Using Python

## 📖 About

A fun computer vision project inspired by Harry Potter’s invisibility cloak!  
This application uses OpenCV and NumPy to create a live video effect that makes a red-colored cloak appear invisible in real time.

---

## 🧠 Concepts Used

- **Image Thresholding**
- **Image Masking**
- **Color Space Conversion (BGR to HSV)**
- **Live Video Capture with OpenCV**
- **Bitwise Image Operations**
- **Morphological Transformations**

---

## 🎥 How It Works

The application captures the background for a few seconds, then detects red-colored areas in each video frame. These red regions are replaced with the previously captured background, creating the illusion of invisibility.

---

## 🛠️ Installation

Make sure you have Python installed. Then install OpenCV:

```bash
pip install opencv-python
