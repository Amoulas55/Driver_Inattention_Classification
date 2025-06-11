# 🧠 Driver Inattention Classification with Deep Learning

This repository presents a deep learning pipeline for classifying driver inattention behaviors using dashboard camera images. The project demonstrates all key stages of an image classification task, from preprocessing and augmentation to CNN training and evaluation.

## 📂 Project Structure

```
Driver_Inattention_Classification/
├── data/                            # Placeholder for dataset (not included)
├── notebooks/                       # Jupyter notebooks for the pipeline
│   ├── Task_1-7.ipynb               # EDA, preprocessing, augmentation
│   ├── Task_8.ipynb                 # CNN training & evaluation
│   └── Task_10_Kaggle.ipynb         # Submission preparation
├── figures/                         # Accuracy/loss curves, evaluation visuals
├── docs/
│   └── driver_inattention_task_summary.txt  # Task summary
├── requirements.txt                 # Python dependencies
├── README.md                        # Project overview
```

## 🔍 Project Overview

This project focuses on detecting distracted driver behavior using deep learning. The approach includes:

- ✅ Exploratory Data Analysis  
- ✅ Data Cleaning & Augmentation  
- ✅ CNN model training and tuning  
- ✅ Evaluation using accuracy and confusion matrix  
- ✅ Submission formatting

The dataset included 10 driver activity classes, such as safe driving, texting, or drinking. Data augmentation techniques were used to address class imbalance and enhance generalization.

## 🧠 Models Used

- Convolutional Neural Networks (CNN)
- Dropout, Batch Normalization, MaxPooling
- Augmentation with Keras `ImageDataGenerator`

## 📚 Notebooks Summary

| Notebook            | Description                                         |
|---------------------|-----------------------------------------------------|
| `Task_1-7.ipynb`     | Image preprocessing, EDA, and augmentation          |
| `Task_8.ipynb`       | Model definition, training loop, evaluation metrics|
| `Task_10_Kaggle.ipynb` | Output formatting for competition-style submission |

## 📑 Project Documentation

For a detailed breakdown of the steps, see:  
📄 [`docs/driver_inattention_task_summary.txt`](docs/driver_inattention_task_summary.txt)

## 📈 Evaluation Highlights

- Class distribution analysis  
- Model accuracy and loss over epochs  
- Confusion matrix analysis  
- Augmentation impact assessment
