# Face Verification System (1:1 Biometric Matching)

##  Project Overview
The goal of this project is to develop a "Digital Doorman" system capable of verifying whether two face images (e.g., an ID photo and a selfie) belong to the same person. This is formulated as a binary classification problem (1 = same person, 0 = different people).

##  Dataset
* **Source:** Labeled Faces in the Wild (LFW) deep-funneled dataset.
* **Structure:** The dataset was balanced to contain 3,000 "same person" pairs and 3,000 "different people" pairs.

##  Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-learn (Random Forest, Logistic Regression)
* **Deep Learning/Computer Vision:** CNN Embeddings 
* **Data Processing & Visualization:** Pandas, NumPy, Matplotlib, Seaborn

##  Methodology
1. **Data Preprocessing:** Image extraction and pair matching.
2. **Feature Engineering:** Extracted high-dimensional facial features using CNN embeddings. Calculated Euclidean distance and Cosine similarity between image pairs.
3. **Modeling:** Trained and compared baseline models (Logistic Regression) against tree-based ensembles (Random Forest) using the extracted embeddings.
4. **Evaluation:** Assessed models based on Confusion Matrix, F1-Score, and ROC-AUC metrics.

##  Key Results
* **Champion Model:** CNN Embeddings + Random Forest.
* **Conclusion:** The use of deep learning embeddings significantly reduced misclassifications compared to relying solely on basic image features.

##  Team Contribution
This was a collaborative academic project. My primary contributions included data preprocessing, model evaluation (ROC-AUC analysis), and synthesizing the final analytical report.
