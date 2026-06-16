#  ♻️ Smart Waste Classification Using Convolutional Neural Networks (CNN)
## 📖 Overview

Waste segregation is an essential step toward efficient recycling and environmental sustainability. Manual waste sorting is time-consuming, error-prone, and inefficient. This project presents an AI-powered Smart Waste Classification System that automatically classifies waste images into different categories using a Convolutional Neural Network (CNN).

**The model is trained on the RealWaste dataset and can accurately identify different types of waste, helping automate the waste segregation process.
**---
## 🎯 Objectives

- Automate waste classification using Deep Learning.
- Improve waste segregation accuracy.
- Reduce manual effort in waste management.
- Support recycling through intelligent waste identification.
  *---*
  ✨ Features

- Image-based waste classification
- CNN-based deep learning model
- Data augmentation for better generalization
- Multi-class waste prediction
- Interactive Gradio web interface
- Displays predicted class with confidence score
*--*
   🗂️ Waste Categories

The model classifies waste into the following categories:
- 🍎 Food Organics
- 🍾 Glass
- 🔩 Metal
- 📄 Paper
- 🧴 Plastic

---
🏗️ Project Workflow

```
Input Waste Image
        │
        ▼
Image Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
CNN Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Prediction
        │
        ▼
Waste Category + Confidence Score
```
🧠 CNN Architecture

The model consists of:

- Convolution Layers
- ReLU Activation
- MaxPooling Layers
- Flatten Layer
- Dense Layers
- Softmax Output Layer

- 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| TensorFlow / Keras | Deep Learning Framework |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Scikit-learn | Performance Metrics |
| Gradio | Web Interface |
| Google Colab | Model Training |


## 📊 Model Performance

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Example Output:

```


## 📁 Project Structure

```
Waste-Classification-CNN/
│
├── app.py
├── waste_classifier.ipynb
├── best_model.keras
├── requirements.txt
├── README.md
│
├── screenshots/
│   ├── interface.png
│   ├── prediction.png
│   ├── accuracy.png
│   └── confusion_matrix.png
│
├── results/
│   ├── classification_report.txt
│   ├── accuracy_graph.png
│   └── loss_graph.png
│
└── presentation/
    └── Waste_Classification_Presentation.pdf
Prediction : Plastic
Confidence : 99.12%
```
