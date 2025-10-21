# 🩺 Diabetes Prediction using Machine Learning

A step-by-step **machine learning pipeline** for predicting diabetes using the **Pima Indians Diabetes Dataset**.  
This project demonstrates data preprocessing, model training, and evaluation using **Python** and **scikit-learn**.

---

## 🚀 Features

- Load and preprocess raw medical data  
- Replace invalid `0` values with `NaN`  
- Impute missing values using the mean  
- Standardize features using `StandardScaler`  
- Split data into training and testing sets  
- Train a **Logistic Regression** model  
- Evaluate model accuracy, confusion matrix, and classification report  

---

## 🧩 Tech Stack

- **Language:** Python 🐍  
- **Libraries:**  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  

---

## 📘 Steps (Pipeline Overview)

1. **Load data**  
2. **Replace 0s → NaN** for medically invalid columns  
3. **Fill NaN** values with the mean  
4. **Scale** the features  
5. **Split** dataset into train/test sets  
6. **Train** model using Logistic Regression  
7. **Predict** outcomes  
8. **Evaluate** accuracy and model performance  

---

## 📂 File Structure

```
├── diabetes.csv                # Dataset (add your own or use Kaggle version)
├── diabetes_analysis.ipynb    # Main Python script (Also provided diabetes_analysis.py)
├── README.md                   # Project documentation
└── requirements.txt            # Dependencies list
```

---

## ⚙️ How to Run
Open the file in Google Colaboratory or in Jupiter Notebook and run the script
### 1️⃣ Clone the repository
```bash
git clone https://github.com/arikmukherjee/Diabetes_Analysis.git
cd Diabetes_Analysis
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the script
```bash
python diabetes_analysis.py
```

---

## 🧪 Sample Output

```
Accuracy: 0.6948051948051948
Confusion Matrix:
 [[81 19]
 [28 26]]
Classification Report:
               precision    recall  f1-score   support

           0       0.74      0.81      0.78       100
           1       0.58      0.48      0.53        54

    accuracy                           0.69       154
   macro avg       0.66      0.65      0.65       154
weighted avg       0.69      0.69      0.69       154
```
<center>
<img src="confusion_matrix.png">
</center>

<center>
<img src="compare_outcomes.png">
</center>

<center>
<img src="features.png">
</center>

<center>
<img src="model_accuracy.png">
</center>

---

## 📈 Future Improvements

- Use advanced models (Random Forest, XGBoost, SVM)
- Add **hyperparameter tuning** and **cross-validation**
- Implement **ROC curve** and **AUC score**
- Create a **Flask/Streamlit web app** for prediction  

---

## 🧑‍💻 Author

**Arik Mukherjee**  
👨‍🎓 B.Sc. Computer Science Student '25 | M.Sc. Computer Science Student '27 | 
📧 Feel free to connect or suggest improvements!

**Kishan Chandra Ghosh**  
👨‍🎓 B.Sc. Computer Science Student '25 | M.Sc. Computer Science Student '27 | 
📧 Feel free to connect <a href="https://github.com/KishanChandraGhosh">Kishan Chandra Ghosh</a> or suggest improvements!

**Simerjeet Singh Bedi**  
👨‍🎓 B.Sc. Computer Science Student '25 |
📧 Feel free to connect <a href="https://github.com/Simerjeetsingh">Simerjeet Singh Bedi</a> or suggest improvements! 


---

## 🪪 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
