# SoftNexis-Titanic-PROJECT-1-
Exploratory Data Analysis and Visualization of the Titanic Dataset for the SoftNexis Internship.

# Titanic Dataset – Exploratory Data Analysis & Visualization

This repository contains the complete implementation for **Project 1** of the **Soft Nexis Technology Data Science Internship**. The project focuses on cleaning raw passenger data from the Titanic, performing exploratory analysis, and building an interactive data visualization dashboard.

## 📁 Project Structure

The project files have been bundled into the submission archive: `PRATHIBHA_Project1_Titanic_EDA.zip`. Inside, you will find:
* **`PRATHIBHA_Project1_Titanic_EDA.ipynb`** – The complete Jupyter Notebook containing the data cleaning code, individual charts, and the final dashboard panel.
* **`titanic_cleaned.csv`** – The finalized dataset after handling missing records, formatting errors, and filtering.
* **`dashboard_titanic.png`** – A compiled 2x2 visual dashboard panel containing four distinct analytical insights.
* **Individual Charts** – Saved high-quality image outputs (`.png`) representing specific variable distributions.
* **Screenshots** – Verification images showing successful executions of `df.describe()` and missing value counts.

---

## 🛠️ Key Implementation Steps

### 1. Data Cleaning & Preprocessing (Task 1)
* Handled missing values systematically (e.g., imputing missing ages using the median value to avoid breaking downstream statistical routines).
* Synthesized family dimensions into a uniform metric (`FamilySize`) to reveal broader correlation structures.
* Exported the polished tabular data to a new production-ready structure (`titanic_cleaned.csv`).

### 2. Exploratory Data Visualization Dashboard (Task 2)
Using `matplotlib` and `seaborn`, the code consolidates four critical analytical points into a single layout:
* **Chart A (Survival Count):** A clean count display contrasting total survival vs non-survival.
* **Chart B (Age Distribution):** A detailed histogram breaking down passenger counts across individual age buckets.
* **Chart C (Survival Rate by Class):** A clear bar layout mapping how socioeconomic status strongly influenced survival chances.
* **Chart D (Family Size vs Survival):** A visual breakdown mapping safety probabilities across different family sizes.

---

## 📈 Top 3 Analytical Findings

1.  **Socioeconomic Advantage:** Passengers in 1st Class experienced significantly higher survival rates compared to those in 2nd and 3rd Class, proving that room placement and boarding class played a massive role in rescue access.
2.  **The Age Factor:** The age distribution shows a distinct survival spike for young children, indicating that emergency lifeboats actively prioritized youth during evacuations.
3.  **Family Size Dynamics:** Passengers traveling alone or in excessively large families faced lower survival probabilities, while small-to-medium-sized family groups showed higher resilience and survival rates.

---

## 🚀 How to Run the Code Locally

1. Clone this repository or download the source folder.
2. Ensure you have the required analytical libraries installed:
   ```bash
   pip install pandas matplotlib seaborn
