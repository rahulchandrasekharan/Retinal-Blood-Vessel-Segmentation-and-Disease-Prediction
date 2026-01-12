**Retinal Blood Vessel Segmentation & Disease Prediction**

Project Overview
This project focuses on automated retinal blood vessel segmentation and eye disease prediction using deep learning techniques. Retinal blood vessels provide crucial clinical information for diagnosing diseases such as Diabetic Retinopathy and Glaucoma.

The system performs:
- Blood vessel segmentation from fundus images
- Disease classification into Normal, Diabetic Retina, and Glaucoma

Objectives
- Segment retinal blood vessels accurately from fundus images
- Use segmented vessels and deep features for disease prediction
- Classify retinal images into Normal, Diabetic Retina, and Glaucoma
- Provide an AI-assisted screening system for ophthalmic analysis

Dataset
FIVES (Fundus Image Vessel Segmentation) Dataset

Dataset Structure:
FIVES/
train/original
train/ground_truth
test/original
test/ground_truth
data.csv

Methodology

Blood Vessel Segmentation
- Input: Fundus retinal images
- Model: CNN-based segmentation network
- Output: Binary vessel mask
- Loss Functions: Binary Cross Entropy, Dice Loss

Disease Prediction
- Input: Original images or segmented vessels
- Model: CNN-based multi-class classifier
- Classes: Normal, Diabetic Retina, Glaucoma

Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

Evaluation Metrics
Segmentation:
- Dice Coefficient
- IoU
- Pixel Accuracy

Classification:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Results
- Accurate retinal vessel segmentation
- Successful disease classification
- Demonstrates deep learning effectiveness in ophthalmic screening

Future Enhancements
- Explainable AI (Grad-CAM)
- Web deployment
- Additional disease classes

Author
Rahul
Kerala, India
