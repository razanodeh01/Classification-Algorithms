# 🧠 Classification Algorithms (ML Assignment #3)

## 📄 About the Assignment

A machine learning assignment focused on classification algorithms including K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVM), and ensemble methods such as AdaBoost and Random Forest. The models were evaluated using accuracy, precision, recall, F1-score, and ROC-AUC to compare their effectiveness in a medical diagnosis setting using the Breast Cancer dataset.


## 📦 Dataset

- **Dataset Used**: Breast Cancer Wisconsin Diagnostic Dataset.
- **Samples**: 30 features, 2 target classes (Benign = 0, Malignant = 1).
- **Split**: 80% Training, 20% Testing.
- **Preprocessing**:
  - Feature standardization using `StandardScaler`.
  - Dataset evaluation using statistical summaries and visualizations.



## 📊 Assignment Breakdown

### 🔹 Part 1: K-Nearest Neighbors (KNN).
- Implemented using `KNeighborsClassifier`.
- Tested distance metrics: Euclidean, Manhattan, Cosine.
- Optimal `k` determined using GridSearchCV (best: `k = 9`).
- Best performance with Euclidean/Manhattan (Accuracy: 97.37%).

### 🔹 Part 2: Logistic Regression.
- Trained with both L1 and L2 regularization.
- L1 enabled sparse feature selection.
- Outperformed KNN in F1-score and precision.

### 🔹 Part 3: Support Vector Machines (SVM).
- Implemented with kernels: Linear, Polynomial, RBF.
- Best results with **Linear kernel** (Accuracy: 95.61%, ROC-AUC: 99.64%).
- RBF and Polynomial showed lower performance.

### 🔹 Part 4: Ensemble Methods.
- **AdaBoost**: Higher Recall (98.61%), useful for catching positives.
- **Random Forest**: Higher Precision (95.89%) and ROC-AUC (99.37%).
- Both methods outperformed individual models in overall stability.


## 🧪 Evaluation Metrics Used
- Accuracy. 
- Precision.  
- Recall.  
- F1-score.  
- ROC-AUC.  

Each model was evaluated consistently across these metrics to determine its effectiveness and reliability.

## 👥 Authors
- [**Razan Abdalrahman**](https://github.com/razanodeh01)  
- [**Hidaya Mustafa**](https://github.com/HidayaMustafa)

