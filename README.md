# 🌍 COVID-19 Data Tracker

This repository contains a comprehensive exploratory data analysis (EDA) project on the **Our World in Data COVID-19 dataset**. The goal of this project is to visualize and analyze global COVID-19 trends, vaccination progress, and key country-level statistics.

## 📊 Dataset Source

- **Original Dataset**: [owid-covid-data.csv](https://ourworldindata.org/covid-dataset) from Our World in Data
- **Cleaned Dataset**: `cleaned_covid_data.csv` (processed in Jupyter Notebook)

The dataset includes information such as:
- Total cases and deaths
- Daily new cases and deaths
- Vaccination numbers and percentages
- ISO codes and country names
- Population data and testing stats

---

## 🧹 Data Preparation

- Loaded `owid-covid-data.csv` into a Jupyter Notebook
- Removed missing and irrelevant columns
- Filtered out aggregates (like "World", "Africa", etc.)
- Generated a cleaned dataset: `cleaned_covid_data.csv`

---

## 📈 Exploratory Data Analysis (EDA)

The EDA includes:

### 1️⃣ COVID-19 Trends Over Time
- Line plots for total cases and deaths per country
- Daily new cases comparison
- Death rate calculations: `total_deaths / total_cases`

### 2️⃣ Vaccination Progress
- Cumulative vaccinations over time for selected countries
- Bar charts showing `% of population vaccinated`
- Pie chart (optional) for vaccinated vs. unvaccinated breakdown

### 3️⃣ Country-Level Comparisons
- Bar chart: Top 10 countries by total cases
- Bar chart: Top 10 countries by vaccination percentage
- Highlighting countries with the highest death rates

### 4️⃣ Global Visualization (Optional)
- Choropleth map showing:
  - Total COVID-19 cases
  - Vaccination percentages by country

---

## 🧠 Key Insights

- Countries like X, Y, and Z had the fastest vaccine rollout.
- Some countries still have very low vaccination percentages.
- Higher vaccination coverage tends to correlate with lower death rates.
- Countries with poor healthcare systems reported higher fatality rates.

---

## 🛠️ Tools Used

- Python (Jupyter Notebook)
- pandas
- matplotlib
- seaborn
- plotly (for choropleth map)

---

## 📁 Project Structure

```bash
.
├── owid-covid-data.csv          # Raw dataset from OWID
├── cleaned_covid_data.csv       # Cleaned dataset used for EDA
├── COVID-19 Global Data Tracker.ipynb           # Main Jupyter Notebook with code & visualizations
└── README.md                    # Project documentation


---

📌 How to Use
1. Clone this repo:

git clone https://github.com/AmungaBrenda/COVID-19-Global-Data-Tracker.git


2. Open the Jupyter Notebook:

jupyter notebook COVID-19 Global Data Tracker.ipynb

Run the cells step by step to explore the data and visualizations.

---

📬 Contact
Made by Franco Juma
