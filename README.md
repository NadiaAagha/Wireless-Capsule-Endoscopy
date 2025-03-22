# Wireless-Capsule-Endoscopy
This repository contains a CNN-based classification model for Wireless Capsule Endoscopy (WCE) images.  
# Wireless Capsule Endoscopy CNN Model  
This repository contains a deep learning model for **Wireless Capsule Endoscopy (WCE) image classification** using **Convolutional Neural Networks (CNN)**.  

## Dataset  
The dataset used is **Kvasir-Capsule**, which contains **14 different gastrointestinal classes**, including ulcers, polyps, and normal mucosa.  

## Preprocessing  
- Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset.  
- Image size: **128x128 pixels**  
- RGB image format  

## Model Architecture  
- **CNN model** built using TensorFlow & Keras  
- Trained with **ResNet50 & VGG16** for comparison  
- Achieved **96.82% accuracy**  

## How to Run  
1. Open `SMOTECNN.ipynb` in Jupyter Notebook or Google Colab.  
2. Run all cells to train and test the model.  

## Results  
| Model    | Accuracy | Precision | Recall |  
|----------|---------|-----------|--------|  
| CNN      | 89.20%  | 89.34%    | 88.80% |  
| VGG16    | 84.49%  | 84.89%    | 84.49% |  
| ResNet50 | **96.82%** | **96.65%** | **96.82%** |  

## License  
This project is licensed under the **MIT License**.  

## Author  
**Nadia Agha**  
MSIT  
