# 🚦 Traffic Signs Detection Android App

This project is an Android application for **real-time traffic sign detection** using **TensorFlow Lite** and the **MobileNetV2** model. Designed for efficient on-device performance, the app detects and classifies traffic signs from the phone camera input using a lightweight deep learning model.

---

## 🔧 Technologies Used

- **TensorFlow Lite** – For deploying the trained model on Android.
- **MobileNetV2** – A fast and optimized CNN architecture for mobile devices.
- **Android (Java/Kotlin)** – Application development platform.
- **GTSDB Dataset** – The [German Traffic Sign Detection Benchmark](http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset), used for training and evaluation.

---

## 📱 Features

- Real-time detection of traffic signs using the Android camera.
- Fast inference optimized for mobile devices.
- Lightweight model with acceptable accuracy for on-device prediction.

---

## 🧠 Model Training

- The model was trained using the labeled GTSDB dataset.
- After training in Python (Jupyter Notebooks), it was converted to **TFLite** for Android integration.
- The `MobileNetV2` architecture was fine-tuned for the classification of traffic sign categories.

---


