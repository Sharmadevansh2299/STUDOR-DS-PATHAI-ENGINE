# Studor DS Screening Project — PathAI Engine

This project builds:

- Engagement Scoring System  
- Disengagement Prediction Model  
- Course Recommendation Engine  

Dataset used: OULAD (Open University Learning Analytics Dataset)

---

## Installation

Install all dependencies using:

pip install -r requirements.txt

---

## Running on Google Colab

### Step 1 — Upload files

Upload:
- Notebook (.ipynb)
- data/ folder (all CSV files)
- requirements.txt (optional)

---

### Step 2 — Install dependencies

Run at the top of the notebook:

!pip install -r requirements.txt

OR:

!pip install pandas numpy scikit-learn matplotlib seaborn xgboost

---

### Step 3 — Set data path

base = "/content/data"

---

### Step 4 — Run notebook

Run all cells (Runtime → Run all)

---

## Running Locally

### Step 1 — Clone repository

git clone <your-repo-link>  
cd <repo-name>

---

### Step 2 — Create virtual environment

python -m venv venv

---

### Step 3 — Activate environment

Windows:  
venv\Scripts\activate  

Mac/Linux:  
source venv/bin/activate  

---

### Step 4 — Install dependencies

pip install -r requirements.txt

---

### Step 5 — Run notebook

jupyter notebook  

OR  

jupyter lab  

---

### Step 6 — Set data path

base = "./data"

---

## Project Structure

project/  
│  
├── data/  
│   ├── studentInfo.csv  
│   ├── studentVle.csv  
│   ├── vle.csv  
│   └── ...  
│  
├── task1_2_engagement_model.ipynb  
├── task3_recommendation_engine.ipynb  
├── requirements.txt  
└── README.md  

---

## Notes

- Ensure all dataset files are inside the data/ folder  
- No external APIs required  
- Notebook runs end-to-end  

---

## Reproducibility

pip install -r requirements.txt  

Run the notebooks  

---

## Output

- Engagement scores (weekly)  
- Risk predictions + alert system  
- Course recommendations  
