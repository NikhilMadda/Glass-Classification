# Glass-Classification
🔹 Project Summary
Goal: Predict the type of glass (e.g., building windows, tableware, containers) based on its chemical composition.
Approach: Implemented Decision Tree and K-Nearest Neighbours (KNN) classifiers using scikit-learn.
Business Value: Can be applied in forensic investigations (matching glass from crime scenes) or industrial quality control.

🔹 Dataset Info
Dataset: UCI Glass Identification Dataset (glass.csv)
Records: 214 samples
Features: 9 chemical attributes:
RI (Refractive Index), Na, Mg, Al, Si, K, Ca, Ba, Fe
Target (output): Glass type (7 classes)

🔹 Methodology

-Data Preprocessing
Loaded dataset using Pandas.
Separated features (X) and target (y).
Train-test split (80:20).
-Models Implemented
Decision Tree Classifier (criterion = gini, entropy tested).
KNN Classifier (tuned optimal K via error rate analysis).
-Evaluation Metrics
Accuracy, precision, recall, F1-score.
Confusion matrix for misclassification patterns.

🔹 Results

Decision Tree Classifier:
Accuracy ≈ 72–75%
Key features: RI, Mg, Al, Ca contributed most.
KNN Classifier:
Accuracy ≈ 70–73% with optimal K = 5
Error rate decreases initially as K increases, stabilizes after ~5.


<img width="1000" height="793" alt="output" src="https://github.com/user-attachments/assets/210e87e1-6ba3-4ae3-8f61-0378509698a8" />

<img width="1000" height="793" alt="output (1)" src="https://github.com/user-attachments/assets/175587b6-f02f-45a9-a661-1eddba38eb17" />

<img width="1408" height="947" alt="output (2)" src="https://github.com/user-attachments/assets/d6b5fa1f-8609-4cb1-aca8-8d6c25dd1dd4" />

<img width="1383" height="947" alt="output (3)" src="https://github.com/user-attachments/assets/d1ac3633-9ea5-41f9-8e0c-cb61f746a964" />









