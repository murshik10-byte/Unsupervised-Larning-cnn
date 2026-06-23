# Unsupervised-Larning-cnn

#  Cat vs Dog Image Classification using Deep Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red?logo=keras)
![CNN](https://img.shields.io/badge/Model-CNN-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

### Deep Learning-Based Binary Image Classification

*A Convolutional Neural Network (CNN) model for accurately classifying Cat and Dog images.*

</div>

---

#  Project Overview

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow** and **Keras** to perform binary image classification between cats and dogs.

The model is trained on labeled image datasets and learns visual features such as shapes, textures, and patterns to distinguish between the two classes. The project demonstrates the complete deep learning workflow, including data preprocessing, augmentation, model training, evaluation, and prediction.

---

#  Objectives

- Build a robust CNN architecture for image classification.
- Preprocess and augment image datasets.
- Train and validate the deep learning model.
- Evaluate model performance using classification metrics.
- Predict whether an uploaded image contains a cat or a dog.

---

#  Project Structure

```text
Cat-Dog-Classification/
│
├── dataset/
│   ├── training_set/
│   └── test_set/
│
├── model/
│   └── cnn_model.h5
│
├── notebooks/
│   └── Cat_Dog_Classification.ipynb
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

#  Dataset Information

| Attribute | Details |
|------------|----------|
| Problem Type | Binary Classification |
| Classes | Cat, Dog |
| Input Shape | 128 × 128 × 3 |
| Framework | TensorFlow / Keras |
| Model | Convolutional Neural Network |

---

#  Technology Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

#  Model Architecture

```text
Input Layer (128x128x3)
        │
        ▼
Conv2D + ReLU
        │
        ▼
MaxPooling2D
        │
        ▼
Conv2D + ReLU
        │
        ▼
MaxPooling2D
        │
        ▼
Flatten
        │
        ▼
Dense Layer (ReLU)
        │
        ▼
Output Layer (Sigmoid)
```

---

#  Project Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Image Augmentation
      ↓
CNN Model Development
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Prediction & Testing
```

---

#  Results

The trained CNN model successfully classifies cat and dog images with high accuracy and demonstrates strong performance on unseen test images.

### Evaluation Metrics

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Prediction Accuracy

---

#  Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/cat-dog-classification.git
```

### Navigate to Project Folder

```bash
cd cat-dog-classification
```

### Install Required Libraries

```bash
pip install tensorflow numpy matplotlib
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

---

#  Sample Output

### Model Predictions

| Input Image | Prediction |
|------------|------------|
| Cat Image |  Cat |
| Dog Image |  Dog |

### Training Visualizations

- Accuracy Curve
- Loss Curve
- Prediction Examples

---

#  Future Enhancements

- Transfer Learning (VGG16, ResNet50)
- Streamlit Web Application
- Real-Time Camera Prediction
- Model Deployment using Flask or FastAPI
- Cloud Deployment

---

#  Author

**Murshid K**

Machine Learning & Deep Learning Enthusiast

GitHub: https://github.com/murshik10

---

#  Show Your Support

If you found this project useful, please consider giving it a **Star** on GitHub.

---

<div align="center">

### Built with  using TensorFlow & Deep Learning

</div>
