# HOG-SVM Medical Diagnoser

A machine learning project for automated pneumonia detection from chest X-ray images using **Histogram of Oriented Gradients (HOG)** feature extraction and a **Support Vector Machine (SVM)** classifier.

---

## Project Overview

Early detection of pneumonia from chest X-ray images can assist healthcare professionals in diagnosis. This project implements a classical machine learning pipeline that extracts HOG features from chest X-ray images and classifies them using an RBF Support Vector Machine.

---

## Features

- Chest X-ray image preprocessing
- HOG feature extraction
- RBF SVM classifier
- Hyperparameter tuning using GridSearchCV
- Confusion matrix generation
- Classification report
- Prediction on unseen chest X-ray images

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-image
- Scikit-learn
- Matplotlib
- Google Colab

---

## Repository Structure

```text
HOG-SVM-Medical-Diagnoser
│
├── dataset/
├── images/
├── models/
├── notebooks/
├── results/
├── src/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Dataset

This project uses a publicly available Chest X-ray Pneumonia dataset.

> The dataset is **not included** in this repository due to its size.

---

## Getting Started

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/HOG-SVM-Medical-Diagnoser.git
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Open the notebook located in the `notebooks` folder and execute the cells sequentially.

---

## Current Status

🚧 This repository is currently under active development.

Future updates will include:
- Detailed documentation
- Sample outputs
- Model performance metrics
- Screenshots
- Project report

---

## Author

**Bhavanesh Patil**