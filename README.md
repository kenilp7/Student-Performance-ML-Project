## 📚 Student Performance Prediction: End-to-End ML Project with MLOps

This repository contains an **end-to-end machine learning project** for predicting student performance using MLOps principles. The project covers data preprocessing, model training, deployment, and monitoring.

---

## 🚀 Project Overview

This project aims to analyze student performance based on various academic and non-academic factors. The end-to-end ML pipeline ensures **scalability, automation, and reproducibility**.

### 🔥 Key Features:
- **Data Processing**: Cleaning, feature engineering, and handling missing values.
- **Model Training**: Multiple ML models trained and evaluated.
- **MLOps Integration**: CI/CD pipeline, model monitoring, and logging.
- **Deployment**: API serving with Flask/FastAPI.

---

## 🏗️ Project Structure

```
📂 Student-Performance-ML-Project
│── 📂 data              
│── 📂 artifacts         
│── 📂 src                
│   ├── 📂 components
│   ├── 📂 pipeline
│   ├── exception.py
│   ├── logger.py
│   ├── utils.py         
│── 📂 experiments        
│── requirements.txt      
│── README.md            
│── Project Plan        
│── setup.py               
```

---

## 📊 Dataset

- The dataset consists of **student-related factors** such as study time, attendance, past grades, etc.
- Available in `data/` directory.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/kenilp7/Student-Performance-ML-Project.git
cd Student-Performance-ML-Project
```

### 2️⃣ Create a Virtual Environment & Install Dependencies
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 🏋️ Model Training

```bash
python src/experiments/model_training.ipynb
```

---
