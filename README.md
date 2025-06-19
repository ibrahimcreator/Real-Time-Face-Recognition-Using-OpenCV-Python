# 🤖 Real-Time AI Hand Gesture Recognition System

A real-time hand gesture recognition system designed to bridge communication for the deaf and dumb, utilizing cutting-edge AI and computer vision technologies. This project is engineered with Python, OpenCV, and MediaPipe for hand tracking, alongside machine learning for gesture classification.

> 🚀 **Capstone Mini-Project | Sep 2023 - Dec 2023**

---

## 📈 Project Summary

This system enables seamless human-computer interaction using hand gestures as input signals:

* 🔄 **Real-Time Recognition**: Live camera feed detects and classifies hand gestures with instant feedback.
* 🔍 **Precise Landmark Detection**: MediaPipe powers accurate hand and finger tracking with 21-point landmarks.
* 📊 **ML Integration**: Hand gestures are trained and predicted using **RandomForestClassifier** from Scikit-learn.
* 🔹 **GUI Interface**: Built with **Tkinter** for an accessible and user-friendly interface.
* 🕵️ **Assistive Focus**: Designed specifically to support communication for the deaf and mute community.

---

## 📚 Key Learnings

* Real-world experience using **MediaPipe** and **OpenCV**
* Model training and evaluation with **Scikit-learn**
* GUI development using **Tkinter**
* Importance of accessibility in software

---

## 🌐 Tech Stack

| Component    | Technology            |
| ------------ | --------------------- |
| Programming  | Python 3              |
| Libraries    | OpenCV, MediaPipe     |
| ML Framework | Scikit-learn          |
| Classifier   | Random Forest         |
| GUI          | Tkinter               |
| IDE          | VS Code / Jupyter Lab |

---

## 💼 Use Cases

* Deaf & Dumb communication aid
* Human-computer interaction (HCI)
* Gesture-controlled applications

---

## 🔥 Features

* Real-time video stream processing
* Data preprocessing & training from hand landmark points
* Predictive model for static gesture classification
* Modular code design for easy extension

---
## 📊 Repository Structure

```
├── Data Collection.py              # Hand landmark dataset generator
├── Model Training.py               # ML model training (Random Forest)
├── Face Recognition App.py         # Main app with gesture prediction + GUI
├── haarcascade_frontalface.xml     # Face detection model (optional)
├── requirements.txt               # All required packages
```

## 🔧 Installation

```bash
pip install -r requirements.txt
python Data Collection.py
python Model Training.py
python Face Recognition App.py
```

---

## 📍 License

This project is licensed under the MIT License.

---

> ✨ If you found this project interesting or helpful, don’t forget to leave a star.
