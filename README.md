<div align="center">
  <h1>🚀 SpaceX Falcon 9 Landing Prediction</h1>
  <p>
    Capstone project for the <strong>Applied Data Science Capstone</strong> course by <strong>IBM on Coursera</strong>.<br>
    A complete end-to-end Data Science project covering data collection, exploration, visualization, prediction, and dashboarding.
  </p>
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="License: MIT">
</div>

---

## 🎯 Project Goal
The primary objective of this project is to develop a machine learning solution that **predicts whether the first stage of the SpaceX Falcon 9 rocket will successfully land**.  
This prediction can help inform **strategic bidding decisions** for a competing startup in the commercial space launch industry.

---

## 📚 Skills & Concepts Applied
This project demonstrates the full data science lifecycle:

- **End-to-End Data Pipeline** – API requests, web scraping, wrangling, and cleaning  
- **Visualization** – Both static and interactive (Matplotlib, Plotly, Folium)  
- **Machine Learning** – Training and evaluating multiple classifiers (SVM, Decision Trees, Logistic Regression)  
- **Business Communication** – Translating technical findings into actionable insights  

---

## 📂 Project Phases & Contents
Each phase is implemented in a Jupyter Notebook inside the [`notebooks/`](notebooks/) directory.

### 1. Web Scraping & Data Collection  
**Notebook:** `webscraping.ipynb`  
- Extract Falcon 9 launch records from a Wikipedia HTML table using **BeautifulSoup**  
- Convert the table into a **Pandas DataFrame**

---

### 2. API Data Collection & Initial Wrangling  
**Notebook:** `data_collection_api.ipynb`  
- Retrieve launch data from the **SpaceX API**
  - Base: /launches/past
  - Lookups: /rockets, /payloads, /launchpads, /cores (to resolve IDs)
- requests.get(...).json() → pandas.json_normalize() for launch records.
- Resolved IDs via rockets/payloads/launchpads/cores endpoints.
- Clean and format for further analysis

---

### 3. Data Wrangling  
**Notebook:** `data_wrangling.ipynb`  
- Perform exploratory Data Analysis 
- Determine Training Labels

---
### 4. Exploratory Data Analysis (EDA) with SQL  
**Notebook:** `eda_sql_sqllite.ipynb`  
- Load dataset into a **Db2 database**  
- Perform EDA with **SQL queries**

---

### 5. EDA & Visualization  
**Notebook:** `eda_DataVisualization.ipynb`  
- Analyze data with **Pandas** and **Matplotlib**  
- Perform **feature engineering** for ML models

---

### 6. Interactive Visual Analytics with Folium  
**Notebook:** `launch_site_location.ipynb`  
- Map launch sites on **Folium**  
- Visualize success/failure rates per site  
- Compute distances between sites and nearby cities  

---

### 7. Machine Learning Prediction  
**Notebook:** `spaceX_ML_prediction.ipynb`  
- Build a **machine learning pipeline** for landing prediction  
- Train & evaluate models: **SVM, Decision Trees, Logistic Regression**  
- Tune hyperparameters and identify best-performing model  

---

### 8. Interactive Dashboard Development  
**Notebook:** `spacex-dash-app.py`  
- Tasks can be found in `Dashboard_Application_with_Plotly_Dash.pdf` file
- Build a **Plotly Dash** interactive dashboard  
- Features: launch site dropdown, payload slider, interactive charts  
- Includes a callback function to render the success-payload-scatter-chart scatter plot  

---

## 🛠️ Technologies Used
- **Python** – Core language  
- **Jupyter Lab** – Interactive development environment  
- **Requests, BeautifulSoup** – Data collection via APIs & scraping  
- **Pandas, NumPy** – Data wrangling & numerical analysis  
- **SQL (Db2)** – Database querying for EDA  
- **Matplotlib, Plotly, Folium** – Visualization (static & interactive)  
- **Dash** – Interactive dashboards  
- **Scikit-learn** – ML model development & evaluation  

---

## 💻 How to Run Locally

```bash
# 1. Clone the Repository
git clone https://github.com/ShyamSundarVijayakumar/SpaceX-Falcon9-Landing-Prediction.git
cd SpaceX-Falcon9-Landing-Prediction

# 2. Create Virtual Environment (recommended)
python -m venv venv

# Activate Environment
# Windows:
.\venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# 3. Install Dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Lab
jupyter lab
```

## 👨‍💻 Author
<div style="display: flex; align-items: center; gap: 20px"> <img src="https://avatars.githubusercontent.com/u/27292813?s=200" width="100" style="border-radius: 50%; box-shadow: 0 4px 8px rgba(0,0,0,0.2)"> <div> <strong>Shyam Sundar Vijayakumar</strong><br> Data Scientist | Optimization Specialist </div> </div>

---

## 📜 License
This project is licensed under the MIT License.
Shared for educational and portfolio purposes. Attribution is appreciated.

