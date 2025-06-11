# 🚗 U.S. County Commute Data Analysis (ACS 2020)

This project extracts and analyzes U.S. county-level commuting data from the **2020 American Community Survey (ACS 5-Year Estimates)** via the U.S. Census Bureau API.

---

## 📊 Dataset Information

The dataset includes the following:

* **NAME**: County name
* **B08303\_001E**: Total number of workers (age 16+) who do not work from home
* **B08303\_013E**: Number of workers who commute 60 minutes or more
* **Geographic Identifiers**: `state` and `county` FIPS codes

**Source:** [U.S. Census Bureau API - ACS 5-Year Data (2020)](https://www.census.gov/data/developers/data-sets/acs-5year.html)

---

## 📁 Files

* `commute_data.csv` - Raw data extracted from the Census API
* `analysis.ipynb` (to be added) - Jupyter notebook with data cleaning, exploration, and visualization

---

## 📦 How to Use

1. Clone the repo
2. Run the Python script to fetch data:

   ```bash
   python fetch_commute_data.py
   ```
3. Open `commute_data.csv` or begin analysis in Jupyter

---

## 🔍 Possible Analyses

* Percentage of long commuters per county
* Geographic visualization (e.g., choropleth maps)
* Comparison across states or regions
* Correlation with population, urbanization, or infrastructure

---

## 📌 Dependencies

* Python 3+
* `requests`
* `csv`
* (Optional) `pandas`, `matplotlib`, `seaborn` for analysis and visualization

---

## 🧠 Motivation

Commuting times influence productivity, mental health, and city planning. This project aims to surface insights from publicly available census data to help inform policies and research on transportation and infrastructure.

---

## 📜 License

This project uses public government data and is released under the MIT License.

---

## 🙌 Contributions

Pull requests are welcome! Please open an issue first to discuss any major changes.

---

## 👤 Author

* GitHub:https://github.com/obirikan

---

> "Data is the new oil – but only if it's refined."
