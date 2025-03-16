# 🍷 Wine Quality Prediction using Machine Learning  

## 🔍 Overview  
This project aims to **predict the quality of wine** based on its **chemical properties** using **Machine Learning techniques**. The dataset used contains **physicochemical attributes** of red and white wines, helping winemakers and consumers assess wine quality **without human tasting**.  

---

## 📂 Dataset  
The dataset is sourced from **Kaggle** and includes various chemical properties such as **pH, acidity, alcohol content**, and more. Each wine sample is labeled with a quality score, allowing the model to learn patterns and make predictions.  

🔗 **Dataset Link:** https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009/data

### 🔢 Features in Dataset  
- **Fixed acidity**  
- **Volatile acidity**  
- **Citric acid**  
- **Residual sugar**  
- **Chlorides**  
- **Free sulfur dioxide**  
- **Total sulfur dioxide**  
- **Density**  
- **pH**  
- **Sulphates**  
- **Alcohol**  
- **Quality (Target Variable)**  

---

## 🔧 Features  
✔ **Data Preprocessing:** Handling missing values, scaling, and encoding categorical variables.  
✔ **Feature Engineering:** Analyzing correlation, outlier detection, and feature selection.  
✔ **ML Models Applied:**  
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
✔ **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.  
✔ **Google Colab/Jupyter Notebook Support:** Easy to run without local setup.  

---

## 🚀 Installation & Usage  

### 🛠 Prerequisites  
Make sure you have the following installed:  

- **Python 3.x**  
- **Jupyter Notebook or Google Colab**  
- Required Python libraries:  
  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn xgboost
