Overview
This project focuses on detecting stress levels using electroencephalogram (EEG) signals and machine learning techniques. By leveraging signal processing, feature extraction, and classification algorithms, the system achieves 89.96% accuracy using the K-Nearest Neighbors (KNN) algorithm in MATLAB.

Stress is a major mental health concern that affects cognitive function, mood, and overall well-being. This project proposes a non-invasive method to classify stress levels using EEG signals, enabling early intervention and better mental health monitoring.

Features
✔ EEG Signal Preprocessing – Noise filtering and segmentation
✔ Feature Extraction – Entropy-based and statistical feature selection
✔ Machine Learning Classification – KNN, SVM, Decision Tree
✔ Performance Analysis – Sensitivity, Specificity, and Accuracy evaluation

System Workflow
EEG Signal Acquisition: Dataset sourced from PhysioNet (pre-stress and post-stress EEG signals).
Signal Processing: Discrete Wavelet Transform (DWT) to extract EEG frequency bands (Theta, Alpha, Beta, Gamma).
Feature Extraction: 30 statistical and entropy-based features computed.
Feature Selection: Wrapper-based optimization using Grey Wolf Optimizer (GWO).
Classification: Stress detection using KNN, SVM, and Decision Tree algorithms.
Evaluation: Model performance assessed based on accuracy, sensitivity, and specificity.
Technologies Used
MATLAB – Data processing, visualization, and machine learning
Signal Processing Techniques – Wavelet Transform (DWT)
Machine Learning – KNN, SVM, Decision Tree
