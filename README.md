# 📊 Predicting Spain’s Economic Trends Using World Bank Data

## 🧠 Project Overview
This project explores how key economic and demographic indicators influence Spain’s GDP over time. Using data from the **World Bank**, we apply data science techniques to clean, analyze, and model the data, ultimately building a predictive model and simulating a hypothetical future scenario.

The project follows the **CRISP-DM** methodology and is part of a data science blog post assignment.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `cleaned_spain_data.csv` | Cleaned dataset filtered for Spain with missing values handled |
| `spain_gdp_analysis.ipynb` | Jupyter Notebook with full analysis, visualizations, and modeling |
| `README.md` | Project overview and documentation |

---

## 📚 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🔍 Key Insights
- Most influential features: life expectancy, school enrollment, urban population growth.
- Creative insight: energy use per capita is highly correlated with GDP but not independently predictive.
- Best model: Linear Regression (R² = 0.9441, RMSE ≈ $44.6B).
- Hypothetical scenario: Predicted GDP = $4.37T with improved population, energy efficiency, and life expectancy.


---

## 📈 Summary of Findings

- ✅ **Model trained**
  - R² Score: **0.8215**
  - RMSE: **79,665,604,646.72**

- 📈 **Hypothetical scenario**
  - Predicted GDP: **$4,370,354,054,333.03**

- 🔍 **Columns removed due to high correlation**
  - Energy use (kg of oil equivalent per capita)
  - Fertility rate, total (births per woman)
  - Forest area (sq. km)
  - GNI, Atlas method (current US$)
  - GNI, PPP (current international $)
  - Inflation, GDP deflator (annual %)
  - Merchandise trade (% of GDP)
  - Mobile cellular subscriptions (per 100 people)
  - Mortality rate, under-5 (per 1,000 live births)
  - Personal remittances, received (current US$)
  - Population density (people per sq. km of land area)
  - Population, total
  - School enrollment, primary and secondary (gross), gender parity index (GPI)
  - School enrollment, secondary (% gross)
  - Surface area (sq. km)
  - Urban population growth (annual %)

- 📊 **Model comparison**

| Model              | R² Score | RMSE              |
|--------------------|----------|-------------------|
| Linear Regression  | 0.9441   | 44,567,040,000    |
| Ridge Regression   | 0.9345   | 48,261,770,000    |
| Random Forest      | 0.8872   | 63,329,670,000    |

---

## 📝 Acknowledgments
- **World Bank** for the dataset: [https://databank.worldbank.org](https://databank.worldbank.org)
- **scikit-learn** and **seaborn** for modeling and visualization tools
- Project inspired by the **Data Science Blog Post** assignment
