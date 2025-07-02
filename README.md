
# Task 6: K-Nearest Neighbors (KNN) Classification

## 🎯 Objective:
To understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification using the Iris dataset.

---

## 🛠 Tools & Libraries:
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn (KNeighborsClassifier, preprocessing, metrics)

---

## 🧭 Steps Followed:

1. **Load and Explore Data**
   - Used the Iris dataset and removed unnecessary columns.
   - Encoded the categorical target variable (`Species`) into numeric labels.

2. **Preprocessing**
   - Standardized the features using `StandardScaler` for effective KNN performance.

3. **Train-Test Split**
   - Split the dataset into training and testing sets using an 80-20 ratio.

4. **KNN Classification**
   - Trained the model using `KNeighborsClassifier`.
   - Tested different values of **K (1 to 20)** and recorded the accuracy.

5. **Model Evaluation**
   - Selected the best K based on accuracy.
   - Evaluated using **Accuracy Score** and **Confusion Matrix**.

6. **Visualization**
   - Plotted **Accuracy vs. K**.
   - Displayed the **Confusion Matrix**.
   - Visualized **Decision Boundaries** using only the first 2 features for clarity.

---

## 📊 Result:
- Best value of **K** was chosen based on maximum accuracy.
- The model successfully classified the Iris species with high accuracy.
