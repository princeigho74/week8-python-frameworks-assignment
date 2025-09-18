# 📊 CORD-19 Data Explorer

This project explores the **CORD-19 metadata dataset** using **Pandas, Matplotlib, and Streamlit**.  
It demonstrates a typical **data science workflow**: loading, cleaning, analyzing, visualizing, and building an interactive dashboard.

---

## 📂 Project Structure


CORD19-Project/
│── cord19_analysis.ipynb # Jupyter Notebook (exploration, cleaning, visualization)
│── app.py # Streamlit app (interactive dashboard)
│── README.md # Documentation
│── metadata.csv # (optional – dataset file, or link below)


---

## 📥 Dataset
The dataset comes from the [CORD-19](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) project.  

For this assignment, only the **`metadata.csv`** file is needed.  
- Download it from Kaggle or your course resources.  
- Place it in the project folder.  

---

## ⚙️ Installation
Make sure you have Python 3.8+ installed. Then install the dependencies:

```bash
pip install pandas matplotlib wordcloud streamlit jupyter

🧾 Usage
1. Run the Jupyter Notebook

Open the notebook for step-by-step data exploration:

jupyter notebook cord19_analysis.ipynb

2. Run the Streamlit App

Launch the interactive dashboard:

streamlit run app.py

📈 Features

Data Cleaning: Handles missing values, converts dates, extracts year.

Exploration: Statistics, missing values check, abstract word counts.

Analysis:

Publications by year

Top journals publishing COVID-19 research

Word cloud of paper titles

Sources of publications

Streamlit App: Interactive filters, charts, and word cloud.

📝 Example Visualizations

Publications trend over time

Top 10 journals

Word cloud of paper titles

🔮 Reflection

Learned how to work with real-world datasets with missing values.

Understood the importance of cleaning and preparing data.

Gained experience building a Streamlit dashboard for interactive exploration.

👨‍💻 Author: Happy Igho Umukoro
📅 Date: 2025
  
