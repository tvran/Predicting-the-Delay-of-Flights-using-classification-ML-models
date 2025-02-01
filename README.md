# ✈️ Flight Delay Classification Using Machine Learning

This project explores the classification of **flight delays** using **classic machine learning models**, aiming to predict whether a flight will be delayed based on various factors such as departure time, airline, and airport data.

## 📌 Project Overview
- Developed as part of final project assessment for **ELCE 455: Machine Learning with Python (Fall 2024)** course with instructor Professor Dr. Amin Zollanvari
- Dataset: **US domestic flights (January 2019)**
- Best performing model: **Random Forest** (92% accuracy, 0.77 F1-score for delayed flights)
- Implemented models: Logistic Regression, Decision Trees, Random Forest, KNN, AdaBoost

## 📊 Methodology
1. **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
2. **Feature Engineering:** Adding temporal features and spatial-temporal interactions for improved predictive power.
3. **Model Training & Selection:** Evaluated multiple ML models using **cross-validation** and **grid search**.
4. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, and ROC-AUC.

## 🚀 Results & Insights
- **Random Forest** outperformed other models, effectively handling non-linear feature interactions.
- **AdaBoost** performed well but had slightly lower recall for delayed flights.
- Feature engineering, including **departure delay indicators** and **time-based binning**, significantly improved model performance.
- Future improvements: Incorporating **weather data** and **deep learning models** like LSTMs.

## 🔧 Installation & Usage
### 📦 Requirements
- Python 3.9+
- Required libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### ▶️ Running the Model
1. Clone the repository:
   ```bash
   git clone https://github.com/tvran/Forte-stt.git
   cd Forte-stt
   ```
2. Run the preprocessing and model training:
   ```bash
   python main.py
   ```

## 📂 Project Structure
```
📁 Forte-stt/
│── Predicting_the_Delay_of_Flights_Turan.ipynb                # Project notebook
│── README.md                                                  # Project documentation
│── dictionaries.py                                            # Loaded dataset
```

📌 **Institution:** Nazarbayev University, School of Engineering and Digital Sciences, Department of Electrical and Computer Engineering  
📅 **Date:** November 24, 2024  
