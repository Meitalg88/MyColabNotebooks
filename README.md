# Blood Cell Classification Project

## Project Overview
This project focuses on classifying blood cells using deep learning models. We used the **BloodMNIST** dataset, which consists of 17,092 images of 8 different blood cell types. The goal is to assist in medical diagnostics by providing accurate and efficient blood cell classification, reducing manual effort and minimizing errors.

## Team Members
We are a team of three, and each member contributed by building and training a unique model:
- **Meital Gerasi:** Implemented a **DenseNet121** model for fine-tuned classification.
- **Shon Eliav** Built and optimized a **ResNet50** model.
- **Nofar Hamamy:** Developed a simple yet effective **CNN** from scratch.

## Dataset
The **BloodMNIST** dataset, part of the MedMNIST collection, contains:
- **17,092 images** (28x28 pixels each) of blood cells, categorized into 8 types:
  - 0: Basophils
  - 1: Eosinophils
  - 2: Erythroblasts
  - 3: Immature granulocytes
  - 4: Lymphocytes
  - 5: Monocytes
  - 6: Neutrophils
  - 7: Platelets
- Split into:
  - **Training set:** 11,959 images
  - **Validation set:** 1,712 images
  - **Test set:** 3,421 images

## Models
### DenseNet121
### ResNet50
### Simple CNN

## Results
Each model was evaluated using the test set, and performance metrics such as accuracy, precision, recall, and F1-score were calculated to compare the models.
![Alt Text](צילום מסך 2025-02-01 144452.png)

## Motivation
The motivation for this project was to improve medical workflows by leveraging deep learning for automated blood cell classification, ultimately reducing diagnostic errors and enhancing patient care.

### Usage  

There are three files, one for each model:  

1. **DenseNet121** - To run this model, you must download the **BloodMNIST** zip file.  
2. **ResNet50** - Automatically loads the dataset at the beginning of the code (no need to download any file).  
3. **CNN** - Automatically loads the dataset at the beginning of the code.  
