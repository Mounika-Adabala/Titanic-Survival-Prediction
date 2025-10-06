# Titanic Survival Prediction 🚀  

This project predicts passenger survival on the **Titanic dataset** using data visualization, preprocessing, and a **Random Forest Classifier**.  


---

## 📂 Project Structure  

```
Titanic-Survival-Prediction/
│
├── Titanic_EDA.ipynb      # Main Jupyter Notebook (EDA, preprocessing, training, prediction)
├── train.csv              # Training dataset
├── test.csv               # Test dataset
└── resultfile.csv         # Predictions saved after running the notebook
```

---

## ⚡ Features  

- **Exploratory Data Analysis (EDA)**  
  - Survivors vs Dead distribution plot  
  - Survival by Gender plot  

- **Preprocessing**  
  - Missing value imputation  
  - Feature engineering (Age groups, Title extraction)  
  - Encoding categorical variables (`Sex`, `Embarked`)  

- **Model Training**  
  - Random Forest Classifier  
  - Validation accuracy printed (~83.8%)  

- **Prediction**  
  - Predictions on `test.csv` saved in `resultfile.csv`  

---

## 🛠️ Installation  

1. Clone this repository (or download the project folder):  
   ```bash
   git clone https://github.com/your-username/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
   ```

2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Launch Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```

4. Open **Titanic_EDA.ipynb** and run all cells.  

---

## ▶️ How to Run  

1. Place `train.csv` and `test.csv` (from Kaggle Titanic dataset) in the project folder.  
2. Run all notebook cells:  
   - You will see **EDA plots**.  
   - Validation accuracy will be printed.  
   - Predictions will be saved as **resultfile.csv**.  

Example output (`resultfile.csv`):  

```
PassengerId,Survived
892,0
893,1
894,0
...
```

---

## 📊 Example Visualizations  

- **Survivors vs Dead Distribution**  
- **Survival by Gender**  

(Plots appear inside the notebook when you run it.)  

---

## 🤖 Model Used  

- **Random Forest Classifier**  
- Default hyperparameters (can be tuned for better performance)  

---

## 📌 Next Steps  

- Try different models (Logistic Regression, XGBoost, etc.)  
- Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)  
- Feature engineering (family size, deck extraction, etc.)  

---

## 🏆 Accuracy  

- Validation Accuracy: **≈ 83.8%**  

---

## 📜 License  

This project is open-source and free to use for learning and practice.  
