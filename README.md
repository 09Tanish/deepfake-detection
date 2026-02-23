# deepfake-detection
AI-based Deepfake Detection System using CNN to classify real and fake facial images. The model detects manipulated media by analyzing facial inconsistencies and artifacts. Built using TensorFlow, OpenCV and FastAPI for real-time prediction and deployment.
# Deepfake Detection Project – GitHub Repository Setup

## 1. Create This Folder Structure

```
deepfake-detection/
│
├── data/
│   ├── real/
│   └── fake/
│
├── models/
│
├── notebooks/
│   └── deepfake.ipynb
│
├── src/
│   ├── train.py
│   ├── predict.py
│   └── utils.py
│
├── app/
│   └── app.py
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

Move your uploaded notebook into:

```
notebooks/deepfake.ipynb
```

---

## 2. requirements.txt

```
tensorflow
keras
opencv-python
numpy
pandas
matplotlib
scikit-learn
fastapi
uvicorn
python-multipart
```

---


---



```
# 🧠 Deepfake Detection System

This project focuses on detecting deepfake images/videos using Deep Learning.

## 🚀 Features
- Detects real vs fake faces
- Trained CNN model
- Image preprocessing
- FastAPI integration
- Real-time prediction support

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- FastAPI
- NumPy
- Scikit-learn

## 📂 Project Structure

src/ → Model training & prediction scripts  
notebooks/ → Model experimentation  
app/ → FastAPI backend  
models/ → Saved trained models

---

## ⚙️ Installation

Clone the repository:
```

git clone [https://github.com/YOUR_USERNAME/deepfake-detection.git](https://github.com/YOUR_USERNAME/deepfake-detection.git)
cd deepfake-detection

```

Create virtual environment:
```

python -m venv venv
venv\Scripts\activate

```

Install dependencies:
```

pip install -r requirements.txt

```

---

## ▶️ Run FastAPI Server

```

uvicorn app.app:app --reload

```

---

## 🧪 Model Training

```

python src/train.py

```

---

## 🔍 Prediction

```

python src/predict.py

```

---

## 📌 Future Scope
- Video deepfake detection
- Web dashboard
- Real-time webcam detection

---

## 📜 License
MIT License
```

---

## 5. GitHub Push Commands

```
git init
git add .
git commit -m "Initial commit - Deepfake Detection Project"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/deepfake-detection.git
git push -u origin main
```
