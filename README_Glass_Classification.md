
# 🥽 Glass Classification Project

## 📌 Project Overview
This project applies **machine learning classification** techniques to predict the **type of glass** based on its chemical composition.  
The dataset used is the **UCI Glass Identification dataset**, which is often applied in **forensic science** (crime investigations) and **industrial quality control**.

---

## 📊 Dataset
- **Samples:** 214 glass records  
- **Features (inputs):** RI, Na, Mg, Al, Si, K, Ca, Ba, Fe  
- **Target (output):** Glass Type (7 classes)  

---

## ⚙️ Methodology
1. Data preprocessing using **Pandas & NumPy**  
2. Visualization with **Matplotlib & Seaborn**  
3. Models applied:
   - **Decision Tree Classifier**
   - **K-Nearest Neighbors (KNN)**
4. Evaluation with accuracy, classification report, confusion matrix  
5. Visualization of:
   - Confusion matrices
   - Error Rate vs K (KNN)
   - Feature importance (Decision Tree)

---

## ✅ Results

### Decision Tree Classifier
- Accuracy: **69.7%**
- Key Features:
  - Mg (16.3% importance)
  - Ba (16.3% importance)
  - Al (15.1% importance)
  - RI (11.9% importance)
  - Na (11.7% importance)

**Confusion Matrix (Decision Tree):**
![Decision Tree Confusion Matrix](dt_confusion.png)

**Feature Importance:**
![Decision Tree Feature Importance](dt_feature_importance.png)

---

### K-Nearest Neighbors (KNN)
- Accuracy: **67.4%**
- Best K ≈ 5

**Confusion Matrix (KNN):**
![KNN Confusion Matrix](knn_confusion.png)

**Error Rate vs K:**
![KNN Error Rate vs K](knn_error.png)

---

## 🔎 Insights
- Decision Tree slightly outperformed KNN (~70% vs ~67% accuracy).
- Most influential chemical components: **Mg, Ba, Al**.
- Misclassifications occurred between similar glass categories.
- With more hyperparameter tuning or ensembles (Random Forest, SVM), accuracy could improve.

---

## 🛠️ Tools & Libraries
- Python, Jupyter Notebook  
- scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📌 How to Run
1. Clone this repo  
2. Install dependencies:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run the Jupyter Notebook `glassclassification.ipynb`

---

## 📜 Author
**Nikhil Madda**
