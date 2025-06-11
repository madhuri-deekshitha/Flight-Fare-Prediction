
# ✈️ Flight Fare Prediction Using Machine Learning

This project aims to predict flight fares using Python-based data visualization and machine learning techniques. By analyzing historical flight data, the system predicts prices based on various factors like date of journey, departure time, arrival time, airline, source, destination, duration, and stops.

## 🧠 Problem Statement

The traditional fare calculation methods in ride-sharing and airline industries do not account for dynamic factors like traffic, demand, and weather. This project addresses this gap by developing a predictive model using machine learning algorithms to improve fare accuracy and customer satisfaction.

## 🎯 Objectives

- Develop a predictive model using ML algorithms like Linear Regression and Random Forest.
- Visualize data trends using Seaborn and Matplotlib.
- Evaluate model performance using metrics like MAE, RMSE, and R².
- Deploy the model using Flask for real-time predictions.

## 🛠️ Technologies Used

| Tool / Library    | Purpose                            |
|-------------------|-------------------------------------|
| **Python**        | Core programming language           |
| **Pandas**        | Data preprocessing                  |
| **Matplotlib**    | Data visualization                  |
| **Seaborn**       | Statistical visualizations          |
| **Scikit-learn**  | Machine learning models             |
| **Flask**         | Model deployment (Web API)          |
| **Pickle**        | Model serialization                 |

## 📈 Methodology

1. **Data Preprocessing**
   - Handle missing values and encode categorical data.
   - Normalize and extract datetime features.

2. **Exploratory Data Analysis**
   - Heatmaps, scatter plots, bar plots, etc.

3. **Model Training**
   - Used Random Forest Regressor with hyperparameter tuning (RandomizedSearchCV).

4. **Evaluation**
   - MAE, MSE, RMSE, and R² metrics used to assess performance.

5. **Deployment**
   - Model saved using `pickle` and served via Flask.

## 🔍 Results

- Achieved high prediction accuracy using Random Forest.
- Visualizations such as heatmaps and scatter plots helped discover key fare-influencing factors.
- Model successfully predicts flight fares based on user input.
  
## 📌 How to Run Locally

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
```
## 📚 References

- Wes McKinney, *Python for Data Analysis*
- Chris Albon, *Machine Learning with Python Cookbook*
- Kaggle: Flight Fare Dataset
- Scikit-learn, Pandas, Matplotlib & Seaborn documentation

## ✅ Future Scope

- Integrate real-time weather and traffic APIs.
- Deploy the model on cloud platforms.
- Expand dataset to international routes and airlines.

