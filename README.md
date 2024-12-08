# Job Market Analysis: A Data-Driven Approach to Skill Demand

## Overview
This project explores job market trends using a data-driven approach, focusing on roles such as Data Analysts and Business Analysts. By leveraging automated data scraping, predictive modeling, and interactive visualizations, the study provides actionable insights for job seekers and employers.

---

## Table of Contents
1. [Project Objectives](#project-objectives)  
2. [Technologies Used](#technologies-used)  
3. [Repository Structure](#repository-structure)  
4. [Datasets](#datasets)  
5. [How to Run the Project](#how-to-run-the-project)  
6. [Key Insights](#key-insights)  
7. [Contributors](#contributors)   

---

## Project Objectives
- Analyze job market trends for high-demand roles.  
- Identify key technical and soft skills.  
- Predict salary ranges using machine learning models.  
- Provide insights through visualizations and dashboards for diverse audiences.

---

## Technologies Used
- **Programming Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, BeautifulSoup, Selenium  
- **Data Visualization:** Tableau  
- **Tools:** Git, Jupyter Notebook, Word for documentation  

---

## Repository Structure
Job-Market-Analysis/ 
- README.md # Project overview |
- data/ # Datasets
- raw/ # Raw datasets
- processed/ # Cleaned/processed datasets
- visualizations/ # Charts and visual outputs
- scripts/ # Python scripts
- scrapejobs.py # Automated job scraping for Data Analyst roles
- bascraper.py # Automated job scraping for Business Analyst roles
- datacleaning.py # Script for data cleaning and preprocessing
- dataprocessing.py # Merging and feature engineering scripts
- predictionmodel.py # Random Forest Classifier for salary prediction
- mergedjobs.py # Merges all datasets
- notebooks/
Jupyter Notebooks
- analysis.ipynb
Exploratory Data Analysis (EDA) 
- reports/ 
Documentation and reports
- Final_Report.pdf # Full project report 

---

## Datasets
- **Raw Datasets:**  
  - Collected using `scrapejobs.py` and `bascraper.py`.  
  - Fields include job titles, companies, locations, salaries, and descriptions.

- **Processed Datasets:**  
  - `salary_by_title.csv:` Average salaries by job title.  
  - `skills_exploded.csv:` Extracted individual skills.  
  - `processed_with_predictions.csv:` Includes salary range predictions.

- **Visualizations:**  
  - Charts such as treemaps, bar graphs, and heatmaps for skill demand, salaries, and job distributions.

---

## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Job-Market-Analysis.git
   cd Job-Market-Analysis
2. **Install Dependencies:**
   Create a virtual environment and install the required Python libraries.
   ```bash
    pip install -r requirements.txt
3. **Run Scripts**
   Execute the scripts in the following sequence:

- **Data Scraping:** `scrapejobs.py`, `bascraper.py`
- **Data Cleaning:** `datacleaning.py`
- **Data Merging:** `mergedjobs.py`
- **Predictive Modeling:** `predictionmodel.py`

4. **View Visualizations**
- Open Tableau dashboards in the `data/visualizations/` folder for insights.

5. **Jupyter Notebook Analysis**
- Explore `notebooks/analysis.ipynb` for exploratory data analysis and visualizations.

---

### Key Insights
1. **Skill Demand Analysis:**
Python, SQL, and Tableau are the most in-demand technical skills.
Soft skills like communication and leadership are equally critical.

2. **Salary Insights:**
High-paying roles such as Product Manager exceed $300,000 annually.
"Medium" salary range ($50,000–$100,000) accounts for 45% of job postings.

4. **Regional Trends:**
California and Texas dominate job postings, while states like Virginia and Florida show emerging opportunities.

5. **Employment Types:**
Full-time roles account for 96.4% of postings, reflecting strong demand for stable employment.

---

### Contributors
**Group 6 Members:**
- Adithya Enakula
- Vatyam Sarath Kumar
- Urmila Desetty
- Meena Divya Sri Pallapothu
