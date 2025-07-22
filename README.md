# Obesity-Classification-IBM
Supervised Classification Model to predict obesity levels based on various lifestyle and health-related features
# Obesity Level Classification using Logistic Regression

This project implements a supervised classification model to predict obesity levels based on various lifestyle and health-related features. It applies **Logistic Regression** using both **One-vs-All (OvA)** and **One-vs-One (OvO)** strategies.

> 📚 This project is based on concepts learned in the **IBM Machine Learning with Python** course on **Coursera**.

![Made with IBM ML Course](https://img.shields.io/badge/Made%20with-IBM%20ML%20Course-blue?style=flat&logo=coursera)

## 📊 Dataset

The dataset includes features such as:
- Age
- Height and Weight
- Physical activity
- Food habits
- Transportation methods
- ...and more

Target variable: `NObeyesdad` (Obesity Level)

## 🧪 Technologies Used

- Python 3.x
- Jupyter Notebook
- Scikit-learn (LogisticRegression, OneVsOneClassifier, metrics)
- Pandas and NumPy
- Seaborn and Matplotlib

## ⚙️ Steps Involved

1. **Data Preprocessing**
   - Standardization of numerical features
   - One-hot encoding for categorical variables
   - Target label encoding

2. **Modeling**
   - Train/Test split with stratification
   - Logistic Regression with:
     - One-vs-All (OvA)
     - One-vs-One (OvO)

3. **Evaluation**
   - Accuracy score
   - Feature importance visualization for both OvA and OvO models

## 📈 Sample Output

- Accuracy (OvA): ~XX%
- Accuracy (OvO): ~YY%
- Visual plots of feature importances and class distributions

---

## 📂 Files Included

| File | Description |
|------|-------------|
| [`Multi-class-Classification-V2.ipynb`](Multi-class-Classification-V2n.ipynb) | Complete Jupyter Notebook with all preprocessing, modeling, and evaluation steps |
| [`Obesity_level_prediction_dataset.csv`](Obesity_level_prediction_dataset.csv) | Dataset containing demographic, behavioral, and physical features used for classification |
| [`requirements.txt`](requirements.txt) | Dependencies needed to run the notebook |

---

## 🧰 Installation

Clone this repo and install dependencies using:

```bash
git clone https://github.com/Naruto-cyber13/Obesity-Classification-IBM.git
cd Obesity-Classification-IBM
pip install -r requirements.txt
```
---
### 3. Run the model
```

jupyter notebook Multi-class-Classification-V2.ipynb
```
---


