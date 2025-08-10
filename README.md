# 🍷 Wine Quality Prediction

## 📌 Overview  
This project predicts the quality of red wine based on its **physicochemical properties** using machine learning techniques.  
The goal is to analyze the dataset, understand feature importance, train predictive models, and evaluate their accuracy in determining wine quality scores.

## 📂 Dataset  
The dataset used is **winequality-red.csv**, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).  

**Features:**
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

**Target:**  
- **Quality** (integer score between 0–10)

---

## ⚙️ Project Workflow  

1. **Data Loading & Exploration**  
   - Import dataset  
   - Check data types, missing values, and basic statistics  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing feature distributions  
   - Correlation heatmap  
   - Relationship between features and quality  

3. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling  
   - Train-test split  

4. **Model Training**  
   - Logistic Regression  
   - Random Forest Classifier  
   - Gradient Boosting / XGBoost  
   - Support Vector Machine  

5. **Model Evaluation**  
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  

---

## 📊 Results  
- Compared multiple ML algorithms to find the best accuracy  
- Identified key features affecting wine quality  
- Achieved high accuracy with **Random Forest / Gradient Boosting** (depending on tuning)

---

## 🚀 Installation & Usage  

**1. Clone the repository**  
```bash
git clone https://github.com/your-username/wine-quality-predictor.git
cd wine-quality-predictor
```

**2. Install dependencies**  
```bash
pip install -r requirements.txt
```

**3. Run the Jupyter Notebook**  
```bash
jupyter notebook "WINE QUALITY PREDICTION.ipynb"
```

---

## 🛠 Technologies Used  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📜 License  
This project is licensed under the MIT License.
