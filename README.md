# 👁️‍🗨️ Computer Vision Character Recognition

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

A Python-based Computer Vision application designed to detect, extract, and classify alphanumeric characters in real-time. Using webcam integration and machine learning, the script processes live video feeds to identify characters held up to the camera.

---

## 📸 Real-Time Detection

Here is a look at the model processing a live video feed and outputting the predicted classifications.

### Live Camera Processing
<img width="662" height="393" alt="Screenshot 1447-10-16 at 1 28 42 AM" src="https://github.com/user-attachments/assets/26464837-32b8-495a-8654-33c27fa70866" />


### Terminal Classification Output
<img width="313" height="56" alt="Screenshot 1447-10-16 at 1 29 20 AM" src="https://github.com/user-attachments/assets/0fe764e9-3185-4cb5-aae2-83c3f6bf4f72" />

---

## ✨ Key Features

* **Real-Time Video Processing:** Captures and processes live frames using OpenCV.
* **Region of Interest (ROI) Extraction:** Dynamically draws bounding boxes around detected objects/characters to isolate them from the background.
* **Image Preprocessing:** Converts live feeds to grayscale and applies thresholding to optimize the image for the classification model.
* **Alphanumeric Classification:** Passes the processed image through a trained machine learning model to predict the character (e.g., Outputting `['2']`).

---

## 📂 Repository Structure

A lightweight, script-focused architecture for rapid execution:

~~~text
📦 cv-alphabet-recognition
 ┣ 📜 alphabet_detection.py  # Main execution script handling the webcam and ML predictions
 ┗ 📜 README.md              # Project documentation
~~~

---

## 💻 How to Run Locally

To test the computer vision model on your own machine, you will need a functional webcam and Python installed.

**1. Clone the repository**
~~~bash
git clone https://github.com/mohdayandev/cv-alphabet-recognition.git
cd cv-alphabet-recognition
~~~

**2. Install dependencies**
Ensure you have the required computer vision and numerical libraries installed (e.g., OpenCV, NumPy):
~~~bash
pip install opencv-python numpy
~~~
*(Note: If your script requires specific ML libraries like `scikit-learn` or `tensorflow` to load the model, install those as well).*

**3. Start the camera feed**
~~~bash
python alphabet_detection.py
~~~
*A window will open displaying your webcam feed. Hold a character up to the camera to see the bounding box and check your terminal for the predicted class.*

---

## 👨‍💻 About the Developer
**Mohammed Ayan** *Transforming raw data and pixels into intelligent, scalable digital solutions.*

🔗 [Connect with me on LinkedIn](https://linkedin.com/in/mohammed-ayan-94ab6a1b6)  
