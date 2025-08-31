# 🎓 Student Performance Prediction Dashboard

An interactive **Streamlit dashboard** that predicts student performance using a trained machine learning model.  
The project combines **data science (JupyterLab)** for data preparation & model training and **Streamlit (VS Code)** for building a user-friendly dashboard.

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
## Student-performance-dashboard/
├── app.py # Streamlit dashboard (main app)
├── St_Performance.csv # Dataset
├── student_performance_model.joblib # Trained ML model

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
