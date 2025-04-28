# 🫁 PulmoScan: AI-Based Lung Nodule Detection and Classification
📋 Project Overview
PulmoScan is an AI-powered system designed to assist in the early detection and classification of lung nodules from Chest CT-Scan images. By combining deep learning techniques and medical imaging expertise, PulmoScan aims to improve diagnostic accuracy, reduce radiologists' workload, and enable faster, more reliable lung cancer detection.

🚀 Main Features
Nodule Detection:
Using models like YOLOv8, Faster R-CNN, and Mask R-CNN for precise localization of pulmonary nodules.

Nodule Classification:
Applying EfficientNet, DenseNet, ResNet, and Xception to classify nodules as normal, benign, or malignant.

Image Preprocessing & Augmentation:
Normalization, resizing, motion blur, and speckle noise to enhance model robustness and generalization.

Comparative Study:
Performance comparison across different deep learning models to select the best architecture.

🗄️ Dataset
LUNA16 Dataset : Specifically designed for the  detection of pulmonary nodules.
TCIA (The Cancer Imaging Archive) : Contains medical images for various types of cancers.
NIH Chest X-Ray Dataset : Provides annotated chest x rays with associated diagnostics.
Chest CT-Scan images Dataset : for the classification of pulmonary nodules 

Preprocessing:

Resizing images to 224x224 pixels

Normalizing pixel values

Applying augmentation (motion blur, speckle noise , gaussian noise , .. )

🛠️ Models Used
Detection Models:

YOLOv8

Faster R-CNN

Mask R-CNN


Classification Models:

EfficientNet (B0–B7)

DenseNet121

ResNet50

Xception


🧪 Performance Metrics
Accuracy

Precision, Recall, F1-Score

Intersection over Union (IoU) for detection

Processing speed (efficiency)

📈 Results Highlights
PulmoScan models achieved higher detection and classification accuracy compared to traditional AI systems.

EfficientNet provided the best balance between speed and performance for classification.

YOLOv8 excelled in real-time nodule detection.


📚 Scientific Contribution
PulmoScan proposes a hybrid AI approach that improves early lung cancer detection by combining fast, precise object detection models with efficient, accurate classifiers. It addresses challenges like large dataset size, imaging noise, and resource constraints, offering a scalable and deployable solution for healthcare systems.

👥 Team
[Data Wizards]
Composed of :
[Amorri Nour]
[Charrada Yosr]
[Etteib Tessnim]
[Mojaat Meriem]
[Sliti Maram]

