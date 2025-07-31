# 📊 Student Performance Predictor

A machine learning mini-project that predicts students' marks using features like hours studied, attendance, sleep habits, past performance, and more. This project includes data exploration, model training, evaluation, and visualization.

---

## 🔍 Project Overview
- Predicts **Marks Obtained** based on real-life academic and behavioral indicators
- Built using **Linear Regression** on an extended dataset
- Visual insights via correlation heatmaps and prediction plots
- Archived v1 notebook (basic model) for comparison

---

## 📁 Project Structure
```
student-performance-predictor/
├── data/
│   └── student_scores_extended.csv          # Enhanced dataset
├── notebooks/
│   ├── EDA_and_Model_v2.ipynb               # Final working notebook
│   └── archive/
│       └── EDA_and_Model_v1.ipynb           # Basic first version
├── .gitignore
├── README.md
└── requirements.txt (coming soon)
```

---

## 🧠 Features Used
- Hours Studied
- Attendance Percentage
- Sleep Hours
- Study Sessions Per Week
- Past Semester Average
- Parent Education Level (encoded)
- Distractions Per Day

---

## ⚙️ ML Workflow
1. Load and inspect dataset
2. Perform EDA (correlation heatmap, top features)
3. Train-test split
4. Train a Linear Regression model
5. Evaluate using MSE and R² score
6. Visualize predictions vs actual marks

---

## 📦 Future Additions
- Streamlit-based UI for predictions
- Model comparison: Random Forest, Ridge, Lasso, XGBoost
- Feature selection & cross-validation
- `requirements.txt` and deployment-ready packaging

---

## 🚀 How to Run
1. Clone the repo
```bash
git clone https://github.com/chetan-palta/student-performance-predictor.git
cd student-performance-predictor
```
2. Open `notebooks/EDA_and_Model_v2.ipynb` in Jupyter or VS Code
3. Run all cells to train and view results

---

## 🧑‍💻 Built With
- Python, Pandas, Numpy
- Scikit-learn, Seaborn, Matplotlib
- Jupyter Notebook

---

## 📬 Contact
**Chetan Palta**  
GitHub: [chetan-palta](https://github.com/chetan-palta)  
LinkedIn: [linkedin.com/in/chetan-palta](https://linkedin.com/in/chetan-palta)

---

> ⭐ If you found this helpful, consider starring the repo!
