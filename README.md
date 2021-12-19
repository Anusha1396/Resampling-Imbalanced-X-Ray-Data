# Resampling-Imbalanced-X-Ray-Data

National Institutes of Health Chest X-Ray Dataset
This NIH Chest X-ray Dataset is comprised of 112,120 X-ray images with disease labels from 30,805 unique patients. To create these labels, the authors used Natural Language Processing to text-mine disease classifications from the associated radiological reports. The labels are expected to be >90% accurate and suitable for weakly-supervised learning. The original radiology reports are not publicly available but you can find more details on the labeling process in this Open Access paper: ["ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases." (Wang et al.)](https://arxiv.org/pdf/1705.02315.pdf)
# Dataset can be downloaded from: ["NIH Clinical Center"](https://nihcc.app.box.com/v/ChestXray-NIHCC)

# Class descriptions
There are 15 classes (14 diseases, and one for "No findings"). Images can be classified as "No findings" or one or more disease classes:

- Atelectasis
- Consolidation
- Infiltration
- Pneumothorax
- Edema
- Emphysema
- Fibrosis
- Effusion
- Pneumonia
- Pleural_thickening
- Cardiomegaly
- Nodule Mass
- Hernia

# Methodology
Focus on a state of the art deep learning model and compare two resampling strategies to deal with the problem of unbalanced multi-label data to predict multiple labels on images of chest x-rays from the NIH Chest X-ray dataset. A Resampling Algorithm is proposed to deal with the problem of unbalanced dataset. The algorithm is divided into two stages, i.e., Binary classification and Resampling techniques.

# Conclusions
From Resampling we can see that the evaluation parameters such as F1-score Precision and Accuracy have shown significant increase in many labels especially in Oversampling case.

# Outline of code:

- Binary_Resampling.ipynb
- Random_Oversampling.ipynb
- Random_Undersampling.ipynb
