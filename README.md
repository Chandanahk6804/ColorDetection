# 🟡 Real-Time Yellow Object Detection using OpenCV

This is a simple yet effective computer vision project that detects **yellow-colored objects** in real-time using your webcam. It draws bounding boxes around the detected objects using basic image processing techniques — **no deep learning involved**.

---

## 🔍 Project Highlights

- 📸 Uses live webcam feed via OpenCV.
- 🎯 Detects yellow objects based on HSV color thresholding.
- ✂️ Removes noise using morphological operations (erode + dilate).
- 📦 Draws green bounding boxes around yellow regions.
- ✅ Entirely done using traditional image processing — **no deep learning or AI models**.

---

## 🧰 Technologies Used

- Python 3
- OpenCV
- NumPy
- Pillow

---

## 🚀 How It Works

1. Capture live frames from the webcam.
2. Convert BGR image to HSV format.
3. Apply fixed HSV thresholds to isolate yellow pixels.
4. Clean the binary mask using erosion and dilation.
5. Detect contours around the yellow regions.
6. Draw bounding boxes around valid contours.

---
