# 🕵️ San Francisco Crime Data Mining Project

This project focuses on analyzing and extracting patterns from San Francisco crime data using **Data Mining techniques**, with a particular focus on **K-Medoids clustering**. The objective is to explore crime distributions across time and location, and provide insights that could help in urban safety planning.

---

## 📌 Objectives
- Discover hidden patterns in crime incidents.
- Identify high-crime zones using clustering (K-Medoids).
- Analyze how crime varies by district, day, and location.
- Visualize trends and clusters for better understanding.

---

## 🧠 Key Questions
- What are the most common crime types?
- Which Police Districts report the most incidents?
- Are there hotspots of crime based on coordinates (X, Y)?
- Can we segment the city into clusters based on crime frequency and location?

---

## 🛠 Tools & Libraries
- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn
- sklearn (preprocessing)
- scikit-learn-extra (for K-Medoids clustering)

---

## 🔄 Project Workflow
1. **Understanding the Problem**  
   Set the goal: pattern discovery, not prediction.

2. **Data Collection**  
   Dataset: [San Francisco Crime Classification (Kaggle)](https://www.kaggle.com/c/sf-crime/data)

3. **Data Cleaning & Preprocessing**
   - Removed unnecessary columns (e.g., `Descript`, `Resolution`, `Address`)
   - Encoded categorical features
   - Normalized features (StandardScaler)

4. **Exploratory Data Analysis (EDA)**
   - Analyzed top crime categories and districts
   - Visualized distributions over time and geography

5. **Data Mining Techniques**
   - Applied **K-Medoids clustering** on location-based features (X, Y)
   - Explored patterns of high-crime zones

6. **Visualization**
   - Histograms, scatter plots, and pie charts to present insights
   - Clusters plotted on coordinate maps

7. **Documentation & Reporting**
   - All analysis documented in the notebook
   - Conclusions and patterns highlighted

---

## 📊 Example Visualizations
- Top crime categories by frequency
- Clustered map of crime hotspots
- Distribution of crimes over days of the week

---

## 📎 Final Thoughts
This project demonstrates how unsupervised learning (clustering) can be used in real-world scenarios like crime analysis. By combining **EDA** with **data mining**, we uncovered insightful trends and potential action points for city planning and law enforcement.

---

## 📁 Files Included
- `data-mining-project.ipynb` – Jupyter Notebook with all code and analysis
- `README.md` – This documentation
- [Add more if applicable]

---

## 🤝 Let's Connect
If you're interested in discussing data science, crime analytics, or collaboration, feel free to reach out!

---
## Author 
Eng.Abdelrhman Yakout 
