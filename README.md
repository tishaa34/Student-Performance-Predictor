
# 🎓 Student Performance Predictor

A Machine Learning project to predict whether a student will pass based on their academic performance and background information using Logistic Regression and Decision Tree models.

---

## 📁 Project Structure

```
Student-Performance-Predictor/
│
├── student_performance_predictor.ipynb   # Jupyter Notebook with all logic
├── requirements.txt                      # List of required Python packages
├── README.md                             # This file
├── .gitignore                            # Ignored files for version control
└── images/                               # (Optional) folder for screenshots
```

---

## 📊 Dataset

The dataset is from the [UCI Machine Learning Repository – Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

It contains student-related attributes:
- Academic performance (`G1`, `G2`, `G3`)
- Demographics (`age`, `sex`, `address`)
- Lifestyle (`goout`, `failures`, `studytime`)
- Social and support factors

---

## 🚀 Features

- 🔍 Data preprocessing & EDA (Exploratory Data Analysis)
- 🤖 Logistic Regression and Decision Tree modeling
- 📉 Accuracy and confusion matrix output
- 📈 Comparison of model performance
- 🧪 Easy to expand with additional models or visualizations

---

## 🧪 How It Works

- The `G3` (final grade) is used to create a binary classification (`pass` or `fail`)
- Features are preprocessed and encoded
- Data is split into training and test sets
- Models are trained and evaluated for performance

---

## 📈 Results

| Model              | Accuracy  |
|-------------------|-----------|
| Logistic Regression | 70.89%    |
| Decision Tree       | 64.56%    |

Confusion matrices are also displayed for each model to show prediction details.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/Student-Performance-Predictor.git
cd Student-Performance-Predictor
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**

```bash
jupyter notebook
```

---


## ✅ Future Improvements

- Add more models (e.g., Random Forest, SVM, XGBoost)
- Deploy as a Streamlit web app
- Use feature selection techniques
- Integrate with real-time student portals

---


## 🙋‍♀️ Author

**Tisha Dharani**  
Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/tisha-dharani-1a30b2306/) or check out more projects on [GitHub](https://github.com/tishaa.34).

---

⭐️ _If you found this useful, feel free to give it a star on GitHub!_
