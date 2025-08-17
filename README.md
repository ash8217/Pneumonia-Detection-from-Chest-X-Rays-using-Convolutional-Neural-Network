# Medical-AI  
## Image Classification using CNN  

### Project: Pneumonia Detection from X-Ray Images using Convolutional Neural Network  

---Data set link : https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

## Dataset  
- The dataset is structured into **3 folders**: `train`, `test`, and `val`, each containing subfolders for two categories: **Pneumonia** and **Normal**.  
- A total of **5,863 chest X-ray images (JPEG format)** are included, categorized into Pneumonia and Normal.  
- The images were collected from **pediatric patients aged 1–5 years** at **Guangzhou Women and Children’s Medical Center, Guangzhou**.  
- All chest X-rays were part of routine clinical care.  

---

## Data Quality & Annotation  
- Chest radiographs underwent **quality control screening**, removing low-quality or unreadable scans.  
- Diagnoses were graded by **two expert physicians**, with an additional review by a **third expert** for the evaluation set to minimize grading errors.  

---

## Model Development  
- A **Convolutional Neural Network (CNN)** was developed using **Keras** and **TensorFlow**.  

---

## Evaluation  
- Achieved **96.68% training accuracy** and **93.10% testing accuracy**, which is strong given the dataset size and class imbalance.  
- Evaluation metrics and visualization included predicted images with their corresponding percentage probabilities.  

---

## Visualizations  
- Screenshots and plots include:  
  - Model architecture.  
  - Evaluation metrics.  
  - Sample predictions with confidence percentages.  

---

Did able to achieve the training accuracy of **96.68 %** and the testing accuracy of **93.10 %**. That's pretty decent, considering the size and the imbalance nature of the dataset.
