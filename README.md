<div align="center">
  <h1>SpaceX Falcon 9 Landing Prediction</h1>
</div>
<div align="Left">
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="License: MIT">
</div>

### Course Context
This repository contains the capstone project for the **"Applied Data Science Capstone"** course offered by **IBM on Coursera**. It represents the culmination of all concepts learned throughout the specialization, applying the **complete data science lifecycle** to a real-world business problem.

### Project Goal
The primary objective of this project is to build a robust machine learning solution that **predicts whether the first stage of the SpaceX Falcon 9 rocket will successfully land**. This prediction helps inform **strategic bidding decisions** for a competing startup in the commercial space launch industry.

### Skills & Concepts Applied
This project demonstrates the full breadth of the data science pipeline, including:

- **End-to-End Data Pipeline Management**: From API-based data collection to structured wrangling and cleaning.
- **Advanced Visualization Techniques**: Crafting both **static and interactive** visualizations to extract and present insights.
- **Machine Learning Model Development**: Designing, training, and evaluating multiple classifiers to predict landing success.
- **Business Communication**: Translating data findings into actionable insights for stakeholders in a real-world context.

### Project Phases & Contents
Each phase is represented by a Jupyter Notebook file:

1. **Data Collection**  
   📄 `Lab_1_Data_Collection.ipynb`  
   - Accessing and parsing SpaceX API data (JSON)
   - Structuring launch data for analysis

2. **Data Wrangling**  
   📄 `Lab_2_Data_Wrangling.ipynb`  
   - Handling missing data, feature extraction, and transformation
   - Ensuring data readiness for downstream tasks

3. **Exploratory Data Analysis (EDA) - Part 1: SQL**  
   📄 `Lab_3_EDA_SQL.ipynb`  
   - Using SQL queries to uncover initial insights

4. **Exploratory Data Analysis (EDA) - Part 2: Visualization**  
   📄 `Lab_4_EDA_Visualization.ipynb`  
   - Visualizing trends and relationships using Matplotlib, Seaborn, and Plotly

5. **Interactive Dashboard Development**  
   📄 `Lab_5_Interactive_Dashboard.ipynb`  
   - Building a **Dash web application** for interactive data exploration

6. **Machine Learning Model Development**  
   📄 `Lab_6_Model_Development.ipynb`  
   - Training and tuning Logistic Regression, SVM, Decision Tree, and KNN models

7. **Model Evaluation & Reporting**  
   📄 `Lab_7_Model_Evaluation_and_Reporting.ipynb`  
   - Evaluating model performance using accuracy, confusion matrix, and F1-score
   - Recommending the best-performing model and reporting findings

### Technologies Used
- **Python**
- **Jupyter Lab**
- **Requests** (API data retrieval)
- **Pandas**, **NumPy** (data manipulation)
- **BeautifulSoup** (HTML parsing)
- **Matplotlib**, **Seaborn**, **Plotly** (data visualization)
- **Dash** (interactive dashboard)
- **Scikit-learn** (machine learning)
- **SQL** (data exploration)

### How to View/Run the Project
Follow the steps below to clone and run the notebooks locally:

```bash
# 1. Clone the Repository
git clone https://github.com/YourGitHubUsername/SpaceX-Falcon9-Landing-Prediction.git
cd SpaceX-Falcon9-Landing-Prediction

# 2. Set up Virtual Environment (Recommended)
python -m venv venv

# Activate Virtual Environment
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# 3. Install Dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Lab
jupyter lab
```

### Author

<div style="display: flex; align-items: center; gap: 20px">
  <img src="https://avatars.githubusercontent.com/u/27292813?s=200" 
       width="100" 
       style="border-radius: 50%; box-shadow: 0 4px 8px rgba(0,0,0,0.2)">
  <div>
    <p1>Hi there, I'm Shyam Sundar Vijayakumar</p1>
  </div>
</div>


### License
This project is shared for educational purposes and portfolio demonstration. Attribution is appreciated if you reference this work.

### Feedback & Contributions
Feedback, issues, and suggestions are welcome. Feel free to open an issue or fork the repository to contribute!
