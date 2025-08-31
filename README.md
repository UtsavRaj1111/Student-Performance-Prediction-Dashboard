# 🎓 Student Performance Prediction Dashboard


This project is an **interactive machine learning dashboard** built with **Streamlit** that predicts student performance based on academic and lifestyle factors.  
It allows users to input study hours, previous scores, extracurricular activities, sleep hours, and practice papers practiced — then generates a **predicted performance index** using a trained model.

The project workflow is split into two parts:
- **Data Cleaning & Model Training** → performed in **JupyterLab**  
- **Dashboard Development & Deployment** → implemented in **VS Code with Streamlit**  

This combination provides both **data science insights** and an **easy-to-use interface** for prediction and visualization.

---

## 🚀 Features
- 📊 **User Input Panel**: Enter study hours, previous scores, extracurricular activities, sleep hours, and practice papers  
- 🎯 **Prediction Engine**: Predicts student performance index based on trained ML model  
- 📈 **Visualizations**:
  - Correlation heatmap  
  - Scatter analysis with regression lines  
  - Distribution of performance index with prediction highlight  
  - Input impact analysis (study hours vs predicted performance)  

---



## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** → Data manipulation  
- **Matplotlib, Seaborn** → Data visualization  
- **Scikit-learn, Joblib** → Model training & saving  
- **Streamlit** → Interactive dashboard


## Workflow
1. **Data Preparation (JupyterLab)**  
   - Load and clean dataset  
   - Handle categorical variables (`Yes/No` → `1/0`)  
   - Train regression/classification model  
   - Save trained model as `student_performance_model.joblib`

2. **Model Deployment (VS Code with Streamlit)**  
   - Build sidebar inputs for student details  
   - Load trained model for predictions  
   - Display results with performance metrics  
   - Add interactive data visualizations  

---
## Example Prediction
**Input:**  
- Hours Studied: `6`  
- Previous Scores: `75`  
- Extracurricular Activities: `Yes`  
- Sleep Hours: `7`  
- Practice Papers: `3`  

**Output:**  
Predicted **Performance Index** displayed along with charts and insights.  

---
##  Installation & Setup
 1. Clone the repository
```bash
git clone <your-repo-link>
cd student-performance-dashboard


## Create a virtual environment

python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

## Install dependencies
 pip install -r requirements.txt

## Run the Streamlit app
streamlit run app.py

## 📦 Requirements
streamlit
pandas
numpy
scikit-learn
joblib
matplotlib
seaborn

## 🧑‍💻 Tools Used
JupyterLab → Data cleaning, preprocessing, model training

VS Code → Streamlit app development & deployment


  

---
## 📂 Project Structure
├── app.py # Streamlit dashboard (main app)
├── St_Performance.csv # Dataset
├── student_performance_model.joblib # Trained ML model




