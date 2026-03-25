# 🎯 Face Recognition Based Attendance System

## 📌 Overview

This project is a **Face Recognition Based Attendance System** developed using Python and OpenCV. It automates the traditional attendance process by detecting and recognizing faces in real-time through a webcam. Once a face is recognized, the system marks attendance automatically in a CSV file with date and time.

This project demonstrates the practical application of **computer vision and machine learning** in solving real-world problems like manual attendance tracking.

---

## 🚀 Features

* 📷 Face Registration (capture user images)
* 🧠 Model Training using LBPH algorithm
* 🎥 Real-time Face Detection & Recognition
* 📝 Automatic Attendance Marking (IN/OUT)
* 📊 CSV-based attendance storage
* 🖥️ Simple GUI using Tkinter

---

## 🛠️ Technologies Used

* Python
* OpenCV (Computer Vision)
* NumPy
* Pandas
* Tkinter (GUI)

---

## 📂 Project Structure

Face-Attendance-System/

│
├── register.py        # Capture face images

├── train.py           # Train face recognition model

├── main.py            # Run attendance system
│

├── attendance.csv     # Attendance records

├── requirements.txt   # Dependencies

├── README.md          # Project documentation
│

├── dataset/           # Stored face images (not uploaded)

├── trainer/           # Trained model (optional)


---

## ▶️ How to Run

### Register Face

```bash
python register.py
```

### Train Model

```bash
python train.py
```

### Run Attendance System

```bash
python main.py
```

---

## 📊 Output

* Detects face using webcam
* Recognizes user based on trained model
* Marks attendance automatically
* Stores data in `attendance.csv`

Example:

ID,Date,Time,Status
101,2026-03-25,10:15:22,IN

---

## ⚠️ Limitations

* Works best under good lighting conditions
* Accuracy depends on quality of dataset
* Recognizes users based on ID only
* Performance may drop with large datasets

---

## 🔮 Future Improvements

* Display user name along with ID
* Database integration (MySQL/Firebase)
* Mobile/web-based version
* Use deep learning for higher accuracy
* Dashboard for attendance analytics


## ⭐ Acknowledgement

This project is created for academic purposes to demonstrate the use of **face recognition in attendance systems** using Python and OpenCV.

---
