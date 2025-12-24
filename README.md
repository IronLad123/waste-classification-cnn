# Waste Classification using CNN

This project implements an **image-based waste classification system** using a **Convolutional Neural Network (CNN)**.  
The model classifies waste into three categories: **Dry**, **Wet**, and **Hazardous**.

All stages of the project — training, evaluation, error analysis, and inference — are performed **inside a Jupyter Notebook**.

---

## 📌 Project Motivation

Proper waste segregation is essential for recycling and environmental sustainability.  
Manual segregation is inefficient and error-prone.  
This project explores how **computer vision** can automate waste classification using deep learning.

---

## 🎯 Project Objectives

- Build a CNN model for waste classification  
- Evaluate performance using accuracy and confusion matrix  
- Analyze class-wise errors  
- Perform notebook-based inference on unseen images  

---

## 🧠 Model Details

- **Model Type:** Convolutional Neural Network (CNN)
- **Framework:** PyTorch
- **Input Size:** 128 × 128 RGB images
- **Output Classes:**
  - Dry
  - Wet
  - Hazardous
- **Final Accuracy:** ~89%

---

## 📂 Dataset Structure

The dataset is organized into three folders:

waste_dataset/
└── images/
├── dry/
├── wet/
└── hazardous/

yaml
Copy code

> ⚠️ Note: Image files are not included in this repository due to size limitations.  
Users can add their own images following the same structure.

---

## 📊 Evaluation

The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Key Observation
Wet waste is comparatively harder to classify due to visual similarity with other waste types.

---

## 🧪 Inference

Inference is performed directly in the notebook:
- User selects any image using a file dialog
- The model predicts the waste category
- Confidence score is displayed

No web application or deployment framework is used.

---

## 📁 Project Structure

waste-classification-cnn/
├── waste_segmentation.ipynb # Training, evaluation, inference
├── model/
│ └── waste_cnn.pth # Trained CNN model
├── waste_dataset/
│ └── images/
├── README.md
└── .gitignore

yaml
Copy code

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/IronLad123/waste-classification-cnn.git
Install dependencies:

bash
Copy code
pip install torch torchvision matplotlib pillow
Open the notebook:

bash
Copy code
jupyter notebook waste_segmentation.ipynb
Run cells sequentially and upload images for prediction

🎓 Academic Value
This project demonstrates:

Practical use of CNNs

Complete ML workflow

Error analysis and interpretation

Clean and reproducible experimentation

👤 Author
Om Srivastava
GitHub: https://github.com/IronLad123

📜 License
This project is intended for academic and educational purposes only.

y
