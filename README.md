# 📱 Google Play Store Apps Analysis

A comprehensive data exploration and visualization of over **10,000 apps** from the Google Play Store — uncovering trends in ratings, installs, categories, and reviews to better understand what drives app success.

---

## 📊 Project Overview

This project performs **data cleaning, analysis, and visualization** of the Google Play Store dataset.  
It aims to identify key patterns and insights in app ratings, size, installs, and categories.

**Highlights:**
- Cleaned dataset from **10,841 → 9,360** valid records.  
- Explored **ratings**, **categories**, **reviews**, **size**, and **installs**.  
- Visualized relationships between variables to uncover actionable insights.

---

## 🧠 Key Insights

| Metric | Insight |
|--------|----------|
| ⭐ Ratings | Most apps have ratings between **4.0 and 4.7**, indicating strong quality control. |
| 🎮 Categories | **Game** and **Family** are the most common app categories. |
| 💬 Reviews | Majority of apps have fewer than **1M reviews**, with popular ones skewing higher. |
| 📈 Installs | Higher installs are often correlated with higher ratings. |
| 📦 Size | Some apps vary in size (“Varies with device”) — these were handled via category means. |

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis environment  

---

## 📁 Dataset

The dataset is sourced from the **Google Play Store Apps dataset**, containing:
- `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Type`, `Price`, `Content Rating`, etc.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/marvellousadedokun/google-playstore-analysis.git
cd google-playstore-apps-analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open Jupyter and explore the notebook:
```bash
jupyter notebook google-playstore-analysis.ipynb
```

---

## 📈 Example Visuals

Some example plots generated:
- Distribution of app ratings
- Top categories by app count
- Ratings vs Reviews scatter plot
- Installs vs Ratings heatmap



---

## 📚 Future Work

- Predict app ratings based on category, size, and reviews  
- Analyze sentiment from user reviews  
- Deploy an interactive dashboard with **Plotly** or **Streamlit**

---

## 👨‍💻 Author

**ADEDOKUN MARVELLOUS**  
📧 your.adedokunmarvel1@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/adedokun-marvellous/) | [GitHub](https://github.com/marvellousadedokun)

---

## 🏷️ License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
