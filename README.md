# Crime-Type-Prediction-Using-Machine-Learning_project
**📌 Project Overview**
* This project leverages machine learning to analyze crime patterns in Indian cities and predict the most likely crime type in a given location. Using historical crime data (2000-2012), a Random Forest Classifier is trained to rank crime types by probability. The project includes a Streamlit dashboard for user interaction and visualization.

**🔍 Key Features**
* ✅ Crime Data Analysis: Preprocesses and analyzes district-wise crime trends from 2000-2012.
* ✅ Crime Type Prediction: Predicts the likelihood of different crime types occurring in a selected location with an accuracy of **97%**.
* ✅ Machine Learning Model: Uses a Random Forest Classifier for crime type ranking with probabilities.
* ✅ Streamlit Dashboard: A user-friendly interface for selecting states, cities, and years to view predictions.
* ✅ One-Hot Encoding: Encodes categorical features (state, district, year) for model training.
* ✅ Model Persistence: Saves the trained model using joblib for future use.

**🛠 Technologies Used**
* Python (pandas, NumPy, scikit-learn, joblib)
* Machine Learning (Random Forest Classifier)
* Data Preprocessing (One-Hot Encoding, feature engineering)
* Streamlit (Interactive UI for visualization & prediction)
* Matplotlib & Seaborn (Data visualization)

**📝 Dataset**
* The dataset contains district-wise crime statistics from 2000-2012, covering multiple crime types such as murder, robbery, kidnapping, and fraud.

**📊 How It Works?**
* 1️⃣ Preprocess Data: One-hot encoding for categorical variables.
* 2️⃣ Train Model: Fit a Random Forest Classifier to predict crime type ranking.
* 3️⃣ Save Model: Store the trained model using joblib.
* 4️⃣ Build Streamlit UI: Allow users to select location & year for predictions.
* 5️⃣ Predict Crime Probabilities: Rank all crime types by likelihood.


