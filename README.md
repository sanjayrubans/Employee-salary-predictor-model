# Employee-salary-predictor-model
employee salary prediction

Features--
Data Cleaning & Preprocessing

Label Encoding & Standard Scaling

Balancing classes using oversampling/undersampling

Model Training using CatBoostClassifier (91% Accuracy Achieved)

Saving the model with joblib

Streamlit-based web interface with:

Multi-block form inputs (Work Info, Personal Info, Financial Info)

Stylish Navbar and Landing Page

Interactive prediction result (Congrats message / Motivational Quote)

Requirements--
Core Libraries
pandas – Data loading and preprocessing

scikit-learn – train_test_split, LabelEncoder, StandardScaler, resample

catboost – Gradient boosting classifier

joblib – Save and load the trained model

Deployment Libraries--
streamlit – Interactive web app

pyngrok – Expose the local Streamlit app to a public URL

Install dependencies:


pip install pandas scikit-learn catboost joblib streamlit pyngrok
How to Run--
Train the Model--
Open EMPLOYEE salary PREDICT MODEL.ipynb and run all cells:

Cleans and encodes the dataset

Trains the CatBoost classifier

Saves the model as catboost_model.pkl

Launch the UI--
Open UI.ipynb and run the Streamlit app:

Loads the saved model

Hosts the web interface for predictions

Or run locally:


streamlit run app.py
