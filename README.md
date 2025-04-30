# Preprocessing_with_Pipeline
This project involves data preprocessing, feature engineering, and model training on a road traffic accident dataset to predict accident severity. The pipeline uses various encoding techniques (Ordinal, One-Hot), handles missing values, scales numerical features, and tests different hyperparameters using GridSearchCV.  
# Road Traffic Accident Severity Prediction

This project involves data preprocessing, feature engineering, and model training on a road traffic accident dataset to predict accident severity. The pipeline uses various encoding techniques (Ordinal, One-Hot), handles missing values, scales numerical features, and tests different hyperparameters using GridSearchCV.

## 📊 Dataset

The dataset used is `RTA Dataset.csv` which contains details of road traffic accidents including:

- Time of accident
- Driver information
- Vehicle and road conditions
- Casualties
- Environmental factors

## 🔧 Techniques Used

- **Handling Missing Data** using `SimpleImputer`
- **Feature Engineering**:
  - Extracting hour from time
  - Label encoding for target
  - Ordinal encoding for ordered categories
  - One-hot encoding for nominal features
- **Preprocessing Pipeline** using `ColumnTransformer`
- **Modeling**: Logistic Regression
- **Model Tuning** using `GridSearchCV`
- **Evaluation**: Classification report and accuracy score


## 🚀 How to Run

1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the `Preprocessing_with_Pipeline.ipynb` notebook in Jupyter or any compatible environment.

## 🧠 Future Improvements

- Implement additional classifiers like Random Forest or XGBoost.
- Save pipeline with `joblib` for deployment.
- Create an interactive web app using Streamlit or Flask.

## 📬 Contact

For questions or feedback, reach out to www.linkedin.com/in/ganeshbahadurbasnet

).


