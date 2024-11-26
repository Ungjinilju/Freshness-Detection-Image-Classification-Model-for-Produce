# **Freshness Detection: Image Classification Model for Produce**

This repository contains an image classification model designed to assess the freshness of produce. The project utilizes deep learning techniques to classify produce as either **fresh** or **rotten**, providing a valuable tool for quality control in agricultural and retail industries.

---

## 🚀 **Features**
- Classifies produce into **fresh** or **rotten** categories.
- Pre-trained models (e.g., **InceptionV3**, **Xception**) for enhanced accuracy.
- Supports custom datasets with automatic data preprocessing.
- Includes Grad-CAM visualization for interpreting model predictions.
- Modular structure for easy experimentation and model updates.

---

## 📂 **Project Structure**
```plaintext
Freshness-Detection-Image-Classification-Model-for-Produce/
├── Code/
│   ├── Data_Preprocessing/
│   │   └── data_augmentation.py        # Scripts for augmenting the dataset
│   ├── Models/
│   │   ├── train_model.py              # Main script for model training
│   │   └── evaluate_model.py           # Script for model evaluation
│   ├── Visualization/
│   │   └── grad_cam_visualization.py   # Grad-CAM implementation
│   └── Step3/
│       └── 3. Calculate_Total_Rotten_Ratio.ipynb  # Analysis notebook
├── Final_Model/
│   └── [Model Checkpoints and Weights] # Model files (not included in repo due to size)
├── Data/
│   ├── fresh/                          # Fresh produce images
│   ├── rotten/                         # Rotten produce images
│   └── dataset_split/                  # Train, validation, test split
└── README.md                           # Project documentation
