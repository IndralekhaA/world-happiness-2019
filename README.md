# World Happiness Report 2019

This project analyzes the 2019 World Happiness Report to explore how various socio-economic factors influence the happiness levels of countries across the globe.

## 📄 About the Dataset

The dataset includes 156 countries and their scores across key happiness indicators:

* **Happiness Score** (based on survey results)
* **GDP per capita**
* **Social support**
* **Healthy life expectancy**
* **Freedom to make life choices**
* **Generosity**
* **Perceptions of corruption**

> Dataset Source: [Kaggle - World Happiness Report 2019](https://www.kaggle.com/unsdsn/world-happiness)

---

## 📊 Project Objectives

* Analyze the distribution of happiness scores globally
* Identify the top 10 and bottom 10 countries by happiness
* Investigate the relationship between GDP per capita and happiness
* Highlight countries that deviate from expected trends

---

## 🎨 Visualizations

The following visualizations are included in this project:

1. **Histogram** of happiness score distribution - [View the chart](./images/score_dist.png)
2. **Bar chart** of top 10 happiest countries - [View the chart](./images/chart_top_10.png)
3. **Scatter plot** of happiness score vs GDP per capita (with trend line)- [View the chart](./images/happiness_vs_gdp_per_capita.png)
4. **Heat Map** of Correlation Matrix among Columns - [View the chart](./images/correlation_map.png)

---

## 🔎 Key Findings

* Happiness scores range from **2.85 to 7.77**, with most countries scoring between **4.5 and 6.5**.
* The **top-ranked countries** include Finland, Denmark, Norway, and Iceland.
* The **bottom-ranked countries** include South Sudan, Central African Republic, and Afghanistan.
* A **strong positive correlation (\~0.79)** was found between GDP per capita and happiness score.
* Some countries, like **South Korea** and **Japan**, showed high GDP but relatively lower happiness.
* Others, like **Guatemala**, scored higher in happiness despite modest GDP, thanks to strong social bonds and life satisfaction.

---

## 🔧 Project Structure

```
/world_happiness_2019/
├── data/
│   └── 2019.csv
├── images/
│   ├── score_dist.png
│   ├── chart_top10.png
│   ├── happiness_vs_gdp_per_capita.png
│   └── correlation_map.png
├── notebooks/
│   └── happiness_analysis_2019.ipynb
└── README.md

```

---
### 🧠 Conclusion
The 2019 World Happiness Report highlights that happiness is not solely dependent on a nation’s wealth. While a higher GDP per capita generally correlates with greater happiness, it's clear that other dimensions like community strength, health, freedom, and trust have equally powerful effects. Countries aiming to improve citizen well-being must adopt balanced, people-centric policies that go beyond economic indicators to cultivate a more supportive, fair, and fulfilling environment for all.

---

## 🚀 Getting Started

To run the notebook:

1. Clone the repository
2. Ensure `kaggle.json` API key is configured (if pulling from Kaggle)
3. Open `happiness_analysis.ipynb` in Google Colab

```bash
pip install -r requirements.txt
Google Colab notebook
```

---

## 🚀 Future Improvements

* Expand to compare happiness trends over multiple years
* Include interactive visualizations using Plotly or Dash
* Deploy key insights as a web dashboard

---

## ✨ Author

**IndralekhaA**
Data Analyst | Storyteller | Aspiring Machine Learning Specialist
