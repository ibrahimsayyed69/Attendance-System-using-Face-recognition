# Face Recognition Attendance System

A Python-based attendance management system that uses **face detection and face recognition** to automatically identify registered individuals and record their attendance digitally.

## 🎓 Project Information:

* **Project Type:** Mini Project
* **Subject:** Computer Vision
* **Course:** B.Sc. Data Science
* **Year:** TY (Third Year)
* **College:** Western College of Commerce and Business Management
* **Roll No.:** 624022

## 📌 Project Overview

The Face Recognition Attendance System is designed to automate the traditional attendance process. Instead of manually recording attendance, the system uses a webcam to detect and recognize registered faces and records attendance automatically.

The project uses **OpenCV** for computer vision and face recognition, with attendance information stored digitally in a CSV file.

## 🎯 Objectives

* Automate the attendance recording process
* Detect and recognize registered faces in real time
* Reduce manual attendance work
* Maintain digital attendance records
* Make attendance tracking faster and more convenient

## ⚙️ Technologies Used

* **Python**
* **OpenCV**
* **NumPy**
* **Haar Cascade Classifier**
* **LBPH Face Recognizer**
* **CSV**
* **Webcam**

## 🔄 How It Works

### 1. Dataset Creation

The system captures multiple images of a registered person using a webcam. These images are stored as a dataset for training and recognition.

### 2. Face Detection

The system detects faces from the captured images and the live webcam feed using a face detection algorithm.

### 3. Face Training

The collected face images are used to train the **LBPH (Local Binary Patterns Histograms)** face recognition model.

### 4. Face Recognition

During attendance, the system compares the detected face with the trained dataset to identify the registered person.

### 5. Attendance Recording

When a registered person is successfully recognized, their attendance is recorded with their **name, ID, date, and time**.

## ✨ Key Features

* Real-time face detection
* Real-time face recognition
* Automatic attendance marking
* Webcam-based operation
* Digital attendance records
* Simple and user-friendly process
* Contactless attendance recording

## 📁 Project Structure

```text
Face-Recognition-Attendance-System/
│
├── data/
│   └── sample_faces/
│
├── trainer/
│   └── trainer.yml
│
├── attendance/
│   └── Attendance.csv
│
├── dataset.py
├── train.py
├── attendance.py
├── requirements.txt
└── README.md
```

> The project structure may vary depending on the final organization of the files.

## 🚀 Installation

### 1. Clone the repository

```bash
git clone: https://github.com/ibrahimsayyed69/Attendance-System-using-Face-recognition
```

### 2. Open the project folder

```bash
cd Face-Recognition-Attendance-System
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 5. Install the required packages

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

### Step 1 — Create Dataset

Run the dataset creation program to register faces:

```bash
python dataset.py
```

### Step 2 — Train the Model

Train the face recognition model using the collected dataset:

```bash
python train.py
```

### Step 3 — Start Attendance System

Run the attendance program:

```bash
python attendance.py
```

Make sure your webcam is connected and working before running the attendance system.

## 📊 Attendance Records

After successful face recognition, attendance information is stored digitally.

The attendance record can contain:

* **Name**
* **ID**
* **Date**
* **Time**

This makes the attendance data easier to access, manage, and track.

## 💡 Benefits

* Saves time compared to manual attendance
* Reduces errors in attendance recording
* Provides a contactless attendance process
* Maintains digital records
* Simplifies attendance management

## 🔮 Future Improvements

Possible improvements to the system include:

* Cloud-based attendance storage
* Web or mobile dashboard
* Improved face recognition accuracy
* Better security and authentication
* Database integration
* Attendance reports and analytics
* Support for larger numbers of registered users

## ⚠️ Limitations

Recognition performance can vary depending on:

* Lighting conditions
* Camera quality
* Face angle
* Image quality of the training dataset
* Changes in a person's appearance

## 📝 Note

This project was developed as a **Computer Vision mini project** for educational and learning purposes as part of the **B.Sc. Data Science** program.

## 👨‍💻 Author

**Ibrahim Sayyed Jaffer**

TY B.Sc. Data Science Student
Western College of Commerce and Business Management

**Roll No.: 624022**

## 📄 License

This project is available for educational and learning purposes.
