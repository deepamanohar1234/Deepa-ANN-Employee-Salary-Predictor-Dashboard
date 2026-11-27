
# Employee Salary Prediction & Career Analytics Dashboard

# Description
Employee Salary Prediction & Career Analytics Dashboard is an end-to-end deep learning project built with TensorFlow, Keras, and Streamlit. It covers web scraping, data preprocessing, and training an Artificial Neural Network to predict employee salaries based on experience, education, job role, skills, and location, all wrapped in an interactive dashboard for visualizing compensation trends and career analytics.


## 🚀 Key Features

* **Automated Data Collection:** Web scraping pipeline designed to extract job listings, required skills, locations, experience levels, and salary ranges.
* **End-to-End Preprocessing Pipeline:** Automated cleaning, handling of missing values, target scaling, one-hot/ordinal encoding, and multi-label skill extraction.
* **Deep Learning Salary Predictor:** A custom Artificial Neural Network built with TensorFlow and Keras to estimate compensation based on user-defined career profiles.
* **Interactive Career Analytics:** Dynamic visualizations exploring salary distributions across roles, experience tiers, geographic hubs, and in-demand technical skills.
* **What-If Scenario Modeling:** Real-time inference allowing users to test how acquiring new skills, gaining experience, or relocating impacts their projected market value.

---

## 🛠️ Tech Stack

* **Deep Learning & ML:** TensorFlow, Keras, Scikit-learn
* **Data Manipulation & Scraping:** Pandas, NumPy, BeautifulSoup / Selenium
* **Frontend & Visualization:** Streamlit, Plotly / Matplotlib / Seaborn
* **Serialization:** Joblib / Pickle (for saving scalers and encoders)


# Project Structure

```text
Employee Salary Predictor/
|--Salary Data_2.csv              # Raw dataset
|--Salary_Data_2_cleaned.csv      # Preprocessed and cleaned dataset
|--ANN.ipynb                      # Jupyter Notebook for EDA, preprocessing, and model training
|--trained_salary_ann.keras       # Saved trained Keras ANN model 
|--stmapp.py                      # Streamlit web application script for predictions
|--requirements.txt               # Project dependencies
|--screenshots.pdf                # Application UI and output screenshots

```

# Installation
### 1. Clone the respository
```bash
git clone https://github.com
cd employee-salary-prediction
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App
```bash
C:\Users\bjele\OneDrive\Attachments\Desktop\Employee_Salary_Predictor streamlit run stmapp.py
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📄 License

This project is licensed under the MIT .


