# 🎯 Student Performance Prediction using Decision Tree

This project uses a Decision Tree Classifier to predict whether a student will **Pass** or **Fail** based on their study hours, attendance, and assignment submission. The model is trained on a dataset of 50 records and tested on both known and unseen data.

---

## 📊 Dataset

The dataset includes the following columns:

- `ID`: Unique identifier
- `Name`: Student's name
- `StudyHours`: Number of hours studied
- `Attendance`: Attendance percentage
- `Assignments`: 1 (Submitted) or 0 (Not Submitted)
- `Result`: `Pass` or `Fail`

✅ Total Records: 50  
✅ Additional Unseen Data: For real-world testing

---

## 🧠 Model

- **Supervised Learning** using `DecisionTreeClassifier`
- `LabelEncoder` is used to convert categorical `Result` (Pass/Fail) to numerical
- Features: `StudyHours`, `Attendance`, `Assignments`
- Target: `Result`

---

## 🔁 Train-Test Split

- 80% used for training the model  
- 20% used for testing  
- ✅ Also tested on **unseen data** to validate model's generalization

---

## 🛠 Technologies Used

- **Python**
- **Pandas** for data handling  
- **Scikit-learn (sklearn)** for:
  - Preprocessing (`LabelEncoder`)
  - Train-test split
  - **Cross-validation**
  - Decision Tree Classifier  
- **Matplotlib** for visualizing the decision tree  

---

## 📈 Evaluation

- **Classification Report** for precision, recall, f1-score
- **Accuracy Score**
- **Cross-validation** for unseen data verification  
- Model Accuracy: ✅ ~98%

---

## 🌳 Model Visualization

A visual representation of the trained decision tree is generated using `matplotlib`.

![Decision Tree](tree_model.png)

---

## 📂 Files Included

- `student_progress.ipynb` → Jupyter Notebook with full code  
- `student_data.csv` → Dataset with 50 records  
- `tree_model.png` → Visual output of the trained decision tree  
- `README.md` → This file  

---

## 🚀 How to Run

1. Clone this repo  
2. Open `student_progress.ipynb`  
3. Run all cells step by step  
4. Make your own predictions!


