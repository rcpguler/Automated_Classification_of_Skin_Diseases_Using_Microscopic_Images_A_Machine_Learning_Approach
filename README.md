# Automated Classification of Skin Diseases Using Microscopic Images: A Machine Learning Approach



ABSTRACT
This study presents a machine learning-based approach for the automated classification of skin diseases, specifically targeting
morphea and lichen sclerosus, using microscopic images. The proposed method involves a systematic workflow, including image
preprocessing techniques such as resizing, Reinhard normalization, Gaussian filtering, and CLAHE histogram equalization to
enhance image quality. Feature extraction was performed using Gray-Level Co-occurrence Matrix (GLCM) and histogram-based
statistical methods, capturing texture and intensity characteristics of skin tissues. Several classification models, including Support
VectorMachine (SVM), Artificial Neural Network (ANN), Decision Tree (DT), RandomForest (RF), K-Nearest Neighbors (K-NN),
and Logistic Regression (LR), were evaluated using accuracy, precision, recall, and F1 score, with hyperparameter optimization
via grid search. The experimental results revealed that the combined feature set (GLCM + Histogram) achieved the highest performance,
with the RF and K-NN models yielding a 100% in all performance metrics, including accuracy, sensitivity, recall, and
F1-score. The study introduces a novel approach by examining these two diseases simultaneously, offering a reliable tool to support
dermatologists with accurate and quick diagnoses. Future work will focus on expanding the dataset, exploring advanced deep
learning techniques, and integrating clinical metadata to enhance model generalizability.

https://doi.org/10.1002/cpe.70220
