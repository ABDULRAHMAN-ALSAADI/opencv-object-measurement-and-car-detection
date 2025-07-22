# OpenCV Projects: Object Measurement & Car Detection 🚗📏

These are two small projects I built using **OpenCV with Python** to improve my computer vision skills. I followed tutorials and guides from [GeeksforGeeks](https://www.geeksforgeeks.org/python/opencv-python-tutorial/).

---

## ⚙️ Tools Used

- Python 3
- OpenCV (cv2)
- GeeksforGeeks tutorials
- VS Code 
- Test images and videos

---

## 📏 Project 1: Object Measurement from Image

This project measures the **width and height** of objects in an image using OpenCV.

### 🎯 Features:

- Detects object boundaries
- Draws a rectangle around the object
- Measures dimensions in pixels

### 🧠 How it works:

1. Convert image to grayscale.
2. Use threshold or edge detection.
3. Find contours.
4. Measure dimensions using bounding rectangles.

<img width="481" height="307" alt="Screenshot 2025-07-22 160710" src="https://github.com/user-attachments/assets/9c7c9826-a20f-4562-8b41-7d0bb783e85f" />


---

## 🚗 Project 2: Car Detection from Video

This project detects cars in a video using a **pre-trained Haar Cascade Classifier**.

### 🎯 Features:

- Detects moving cars
- Draws rectangles around detected cars
- Can count cars if needed (experimental)

### 🧠 How it works:

1. Load Haar cascade XML file for car detection.
2. Read video frame by frame.
3. Convert to grayscale.
4. Detect cars using the classifier.
5. Draw rectangles on cars.

> ⚠️ Note: The detection may count wrong objects in the video if lighting or video quality is low.

<img width="1920" height="1080" alt="Screenshot 2025-07-22 155141" src="https://github.com/user-attachments/assets/3d6ebf03-94d1-4d76-9c46-8e913371de50" />




