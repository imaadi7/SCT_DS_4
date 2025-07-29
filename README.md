# 🚗 Road Accident Analysis

### About the Project
This is a detailed exploratory data analysis and machine learning pipeline built on a global road accident dataset (~132,000 records and 35 features). The notebook uncovers critical accident patterns and predicts severity (Low / Medium / High) using Random Forest.

---

## 🔍 Key Insights

1. 📅 **Yearly & Monthly Trends** – Identified accident patterns over time, including seasonal spikes.  
2. 🥇 **Top Causes** – Highlighted top 10 accident causes, offering insight into major safety issues.  
3. 🌍 **Region-wise Breakdown** – Revealed geographic hotspots for crashes and high-fatality regions.  
4. 🌦️ **Weather & Road Conditions** – Compared impacts of conditions like rain, fog, and road surface types.  
5. 🏙️ **Urban vs Rural** – Analyzed differences in accident rates and severity in urban versus rural settings.

---

## ⚙️ Feature Engineering

- ✅ `Date` constructed from Year + Month  
- 📆 `Is_Weekend` (1 if weekend, 0 otherwise)  
- 🌡️ `Season` derived from the accident month  
- ⚠️ `Accident_Severity` assigned based on fatalities

---

## 🤖 Machine Learning Model

- **Task**: Predict `Accident_Severity`  
- **Algorithm**: Random Forest Classifier  
- **Evaluation**: Classification report with precision, recall, and F1-score  
- *(Optional)* Feature importance plot showing top predictors like `Road Condition`, `Number of Vehicles Involved`, etc.

---

## 🛠️ Tech Stack

- **Python**  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn  
- **Notebook Environment**: Jupyter / Google Colab

---

## 🧪 Quick Start

1. Clone this repository  
2. Launch `Road_Accident_Analysis.ipynb` in Colab or Jupyter  
3. Run all cells sequentially – data processing, visualization, ML modeling included  

