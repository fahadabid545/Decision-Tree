# 🌸 Iris Dataset Classification using Decision Tree

This project demonstrates a complete machine learning pipeline on the famous **Iris dataset**, including Exploratory Data Analysis (EDA), model training using a **Decision Tree Classifier**, and performance evaluation.

## 📌 Project Highlights

- 🔍 Performed **Exploratory Data Analysis (EDA)** using `pandas`, `seaborn`, and `matplotlib`.
- 🌳 Built a **Decision Tree** model using `scikit-learn`.
- 🧪 Evaluated the model using accuracy score and classification metrics.
- 📈 Visualized data distributions, feature importance, and decision boundaries.

---

## 📂 Contents

- `iris_decision_tree.ipynb` – Jupyter Notebook containing EDA, model training, and evaluation.

---

## 📊 Dataset

- **Source**: `sklearn.datasets.load_iris()`
- **Features**: 
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target**: Iris Species (`setosa`, `versicolor`, `virginica`)

---

## ⚙️ Workflow

1. **Load and explore** the Iris dataset.
2. **Visualize** data distributions and pair plots to understand class separability.
3. **Preprocess** data (if needed) and split into training/testing sets.
4. **Train** a `DecisionTreeClassifier` on the training data.
5. **Evaluate** using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. **Interpret** the model using feature importances.

---

## 🏁 Results

- Achieved high classification accuracy (100%).
- Found petal length and petal width to be the most important features.

---

