# Diabetes_Dataset_Modeling
---

## 📌 Project Overview  
This project leverages machine learning to analyze and predict diabetes outcomes based on key health indicators. Using the **PIMA Indians Diabetes Dataset**, the goal is to build a reliable classification model to predict whether a patient is at risk of diabetes. The project covers the entire machine learning pipeline, including **data preprocessing, exploratory data analysis (EDA), feature engineering, model development, evaluation, and deployment**.

---

## 🎯 Objectives  
1. **Understand Factors Contributing to Diabetes**:  
   - Analyze relationships between key features like glucose levels, BMI, and diabetes history.  
2. **Build Accurate Prediction Models**:  
   - Train, test, and evaluate machine learning models for classification.  
3. **Deploy a Diabetes Risk Prediction Tool**:  
   - Create an interactive application for healthcare professionals to input patient data and receive predictions.  

---

## 🛠️ Features  
- **Data-Driven Insights**:  
  Explore trends and patterns in health-related features that influence diabetes risk.  
- **Machine Learning Models**:  
  Implements various classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forest, XGBoost).  
- **Feature Engineering**:  
  Handles missing values, scales data, and selects the most impactful features for better model performance.  
- **Interactive Deployment**:  
  The project is integrated with Streamlit for real-time diabetes risk predictions.  

---

## 📊 Dataset  
The dataset used is the **PIMA Indians Diabetes Dataset**, which includes health data for over 700 individuals.  

### Key Features:  
- **Pregnancies**: Number of pregnancies.  
- **Glucose**: Plasma glucose concentration.  
- **BloodPressure**: Diastolic blood pressure.  
- **SkinThickness**: Triceps skinfold thickness.  
- **Insulin**: 2-hour serum insulin levels.  
- **BMI**: Body mass index.  
- **DiabetesPedigreeFunction**: A function that scores likelihood of diabetes based on family history.  
- **Age**: Age of the patient.  
- **Outcome**: Diabetes diagnosis (1 = Positive, 0 = Negative).  

---

## 🚀 Machine Learning Pipeline  
1. **Data Preprocessing**:  
   - Impute missing values and handle outliers.  
   - Normalize features to improve model performance.  
2. **Exploratory Data Analysis (EDA)**:  
   - Visualize feature distributions and identify correlations with diabetes outcomes.  
3. **Feature Selection & Engineering**:  
   - Identify the most predictive features using statistical methods.  
4. **Model Development & Evaluation**:  
   - Train multiple classification models (e.g., Logistic Regression, Random Forest, XGBoost).  
   - Evaluate models using metrics like accuracy, precision, recall, and F1-score.  
5. **Deployment**:  
   - Build an interactive prediction tool using **Streamlit**.  

---

## 💻 Usage  
### To Run Locally:  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/KayLiz/Diabetes_Dataset_Modeling.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd Diabetes_Dataset_Modeling  
   ```  
3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
4. Run the Streamlit app:  
   ```bash  
   streamlit run app.py  
   ```  
5. Open the app in your browser and input data to receive predictions.  

---

## 📂 Repository Structure  
```  
├── app.py               # Streamlit app file for diabetes prediction.  
├── data/                # Contains the dataset used for training and testing.  
├── notebooks/           # Jupyter notebooks for EDA and model development.  
├── models/              # Saved pre-trained models.  
├── requirements.txt     # Python dependencies.  
└── README.md            # Project documentation.  
```  

---

## ⚙️ Models Implemented  
- Logistic Regression  
- Decision Trees  
- Random Forest  
- XGBoost  

---

## 📈 Results  
The models achieved the following performance metrics on the test set:  
- **Accuracy**: X.XX  
- **Precision**: X.XX  
- **Recall**: X.XX  
- **F1-Score**: X.XX  

*Details on model performance can be found in the notebooks folder.*  

---

## 👥 Contributors  
- **Enkeshie Parris**  
  *Lead Developer & Data Scientist*  

---

## 📧 Contact  
For questions or suggestions, feel free to reach out via [LinkedIn](https://www.linkedin.com) or email me directly.  

