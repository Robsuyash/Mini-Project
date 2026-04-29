# DeepFace Detection Using CNN

A full-stack DeepFace Detection project that uses a **Convolutional Neural Network (CNN)** for face detection and recognition.
---

# 📌 Project Overview

This project is designed to detect and recognize faces using a CNN-based deep learning model. Users can upload images through the frontend, while the backend processes the input and returns detection results.

The system combines:

* **Deep Learning (CNN)** for face detection and recognition
* **Frontend** for image upload and result display
* **Backend API** for processing requests and connecting with the ML model
---

# 🚀 Features

* Face Detection using CNN
* Real-time or Image-based Face Recognition
* Upload image through frontend
* Backend API integration
* Detection confidence score
* User-friendly UI
* Fast prediction response
* Modular frontend-backend architecture

---

# 🛠️ Tech Stack

## Frontend

* HTML
* CSS
* JavaScript
* React
* Bootstrap/Tailwind CSS

## Backend

* Python
* Flask / FastAPI
* REST API

## Machine Learning

* TensorFlow
* CNN (Convolutional Neural Network)

---

# 📂 Project Structure

```bash
DeepFace-Detection/
│
├── backend/
│   ├── app.py
│   ├── model/
│   │   ├── cnn_model.h5
│   │   └── predictor.py
│   ├── routes/
│   ├── uploads/
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   ├── package.json
│   └── styles/
│
├── dataset/
├── README.md
└── .gitignore
```

---


# 🧠 CNN Model Workflow

1. Input image uploaded from frontend
2. Backend receives image through API
3. Image preprocessing using OpenCV
4. CNN model performs feature extraction
5. Face detection and recognition
6. Prediction result returned to frontend
7. UI displays detected face and confidence score

---

# 📸 How It Works

1. User uploads an image or starts webcam.
2. Frontend sends image to backend API.
3. Backend loads CNN model.
4. Face detection process begins.
5. Prediction results are generated.
6. Result displayed on frontend.

---

# 📷 Sample Output

```bash
Detected Face: John Doe
Confidence Score: 96.8%
```

---

# 🔌 API Endpoints

## Upload Image

```http
POST /predict
```

### Request

```json
{
  "image": "uploaded_image"
}
```

### Response

```json
{
  "status": "success",
  "prediction": "Face Detected",
  "confidence": "96.8%"
}
```

---

# 📊 Future Improvements

* Add real-time webcam tracking
* Improve model accuracy
* Add multiple face detection
* Authentication system
* Cloud deployment
* Face mask detection support

---

# 👨‍💻 Contributors

| Name                |
| ------------------- |
| Suyash              |
| Purvi Maheshwari    |
| Mihika Puri         |
| Kanhaiya Kumar      |
| Raanu Kumar Mishra |

---

# 🎓 Guidance

Under the guidance of **Mr.Sunil Kumar Sawant**.

---
