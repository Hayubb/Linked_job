# LinkedIn Job Analysis 🧠💼

This project dives into real-world LinkedIn job postings to extract valuable insights and build a machine learning model that can predict job titles based on job descriptions.

## 🔧 Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Logistic Regression

## 📊 Key Insights
- "Engineer" and "Manager" are among the most frequently posted roles.
- Remote job listings are highly represented, indicating a shift toward flexible work.
- Top keywords in job descriptions include **Python**, **SQL**, and **communication skills**—a strong signal of in-demand competencies.

## 🤖 Model Evaluation
We trained a **Logistic Regression** classifier on cleaned and vectorized job descriptions:
- **Accuracy:** ~93%
- **Strength:** Lightweight, interpretable, and effective for text classification tasks.

## 📁 Folder Structure
- `Linkedin_job_analysis.ipynb`: Main notebook with EDA, preprocessing, modeling, and evaluation.
- `data/`: Original dataset (not included due to size/privacy).
- `README.md`: This file.

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/Hayyub/LinkedIn-job-analysis.git
