# SpaceX-Falcon-9-Landing-Prediction 🚀

An end-to-end data science project that analyzes SpaceX Falcon 9 launch data to
understand key factors affecting first-stage landing success and to build
predictive classification models.

---

## Project Objective
- Analyze SpaceX launch data using EDA, SQL, geospatial analysis, and dashboards
- Identify factors influencing Falcon 9 first-stage landing success
- Build and evaluate machine learning models to predict landing outcomes

---

## Data Sources
- SpaceX API (static JSON for reproducibility)
- Curated datasets provided by IBM Skills Network
- Geospatial datasets for launch site analysis

---

## Project Workflow
1. **API Data Collection** – Request and parse SpaceX launch data  
2. **Data Wrangling** – Cleaning, filtering Falcon 9 launches, handling missing values  
3. **Exploratory Data Analysis (EDA)** – Trends by launch site, payload, orbit, and time  
4. **SQL Analysis** – Launch sites, payload statistics, landing outcomes  
5. **Geospatial Analysis** – Folium maps for launch sites, outcomes, and proximity analysis  
6. **Interactive Dashboard** – Plotly Dash app for success analysis by site and payload  
7. **Machine Learning** – Classification models with hyperparameter tuning  

---

## Tools & Technologies
- **Programming:** Python (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn, Folium, Plotly Dash
- **Databases:** SQL (SQLite)
- **Machine Learning:** Scikit-learn
- **Version Control:** Git & GitHub

---

## Machine Learning Models
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

**Best Performing Model**
- **Logistic Regression**
- **Accuracy:** **94.44%**

Evaluation used cross-validation, accuracy comparison, and confusion matrix analysis.

---

## Repository Structure

