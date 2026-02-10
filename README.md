# Task 14: Model Comparison & Best Model Selection

## 📌 Objective
The goal of this task is to compare multiple machine learning models on the same dataset using consistent preprocessing and evaluation metrics, and to select the best-performing model based on business-relevant criteria.

This task helps in understanding **algorithm selection**, a critical skill used by industry ML teams.

---

## 📊 Dataset
**Breast Cancer Dataset (Sklearn)**  
- Auto-generated and saved as CSV
- Binary classification problem  
- Target:
  - `0` → Malignant
  - `1` → Benign

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Joblib  

---

## 🤖 Models Compared
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)

---

## ⚙️ Approach
1. Load and save the dataset as a CSV file.
2. Perform a single train-test split (same split for all models).
3. Apply scaling where required using Pipelines.
4. Train multiple models using identical data.
5. Evaluate models using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
6. Store all evaluation metrics in a comparison table.
7. Visualize model performance using a bar chart.
8. Select the best model based on **F1 Score**.
9. Save the best-performing model for future use.

---

## 📈 Evaluation Metrics
- **Accuracy** – Overall correctness
- **Precision** – Correct positive predictions
- **Recall** – Ability to capture positives
- **F1 Score** – Balance between precision and recall (used for final selection)

---

#Outputs:
<img width="800" height="377" alt="Image" src="https://github.com/user-attachments/assets/91fd412c-c7dc-42f6-b328-ca581c7327c8" />
<img width="1286" height="729" alt="Image" src="https://github.com/user-attachments/assets/bcda6271-b82d-4806-ad89-e8bebd0e0c5f" />

