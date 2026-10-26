🌱 Smart Crop Disease Detection System

📌 Project Overview

The Smart Crop Disease Detection System is a Deep Learning and Computer Vision project that detects diseases in crop leaves from images. It helps farmers identify plant diseases early, reducing crop loss and improving agricultural productivity.

The system uses the PlantVillage Dataset and a CNN Deep learning model to classify crop diseases based on features extracted from leaf images.

---

🎯 Objectives

- Detect crop diseases from leaf images.
- Provide accurate disease predictions.
- Help farmers take timely preventive actions.
- Reduce crop damage and improve yield.

---

🛠 Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Joblib

---

📂 Dataset

PlantVillage Dataset

- Total Images: 54,306+
- Multiple crop species
- Healthy and diseased leaf images
- Publicly available dataset for plant disease classification

---

⚙ Workflow

PlantVillage Dataset
⬇
Load Images
⬇
Image Preprocessing
⬇
Train-Test Split (80:20)
⬇
Model Evaluation
⬇
Prediction on New Images
⬇
Requirements
⬇
README

---

✨ Features

- Upload crop leaf image.
- Automatic image preprocessing.
- Disease prediction using CNN Model.
- Displays predicted disease name.
- Shows prediction confidence.
- Saves trained model for future use.

---

📁 Project Structure

Smart-Crop-Disease-Detection/
│
├── Dataset/
├── Models/
├── Test Image
├── Train_model.py
├── Predict.py
├── preprocessing.py
├── requirements.txt
├── README.md

---

🚀 Installation

1. Clone the repository.
2. Install dependencies:
   pip install -r requirements.txt
3. Download the PlantVillage dataset.
4. Run the training script:
   python train_model.py
5. Predict a disease:
   python predict.py

---

📊 Deep Learning Model

- Algorithm: CNN Model
- Train-Test Ratio: 80:20
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

---

📈 Expected Results

- High disease classification accuracy.
- Fast prediction time.
- Reliable disease identification.
- Easy-to-use system for farmers and researchers.

---

🌾 Future Enhancements

- Mobile application integration.
- Real-time disease detection using a camera.
- Cloud-based prediction service.
- Multi-language support.
- Treatment and fertilizer recommendations.

---

👨‍💻 Developed By

Smart Crop Disease Detection System
Academic Mini/Major Project using Python, Deep Learning, OpenCV, and the PlantVillage Dataset.

---

📜 License

This project is intended for educational and research purposes. You are free to modify and improve it for learning and academic use.

---

🙏 Acknowledgements

- PlantVillage Dataset
- Python Open Source Community
- Scikit-learn
- OpenCV
- NumPy
- Pandas
- Matplotlib
