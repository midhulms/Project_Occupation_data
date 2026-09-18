# Project Occupation Data

Exploratory data analysis of a user demographics dataset — age, gender, occupation and location — used to surface patterns in who the users are and how those traits relate to one another.

## Dataset

`Occupation Data.csv` — 943 user records, 5 columns:

| Column | Description |
|---|---|
| `user_id` | Unique identifier for each user |
| `age` | User age |
| `gender` | User gender (M/F) |
| `occupation` | Self-reported occupation category |
| `zip_code` | US postal code |

This is the classic user-demographics file structure (user_id, age, gender, occupation, zip_code) popularised by the MovieLens `u.user` dataset, commonly used as a lightweight, well-known benchmark for demographic EDA before moving on to messier real-world data.

## What's in the notebook

`Occupation Data.ipynb` walks through:

- **Data loading & cleaning** — reading the CSV with pandas, checking dtypes, nulls and duplicates
- **Univariate analysis** — age distribution, gender split, and frequency of each occupation category
- **Bivariate analysis** — age distribution by occupation, gender balance within each occupation, and how occupation mix varies across regions implied by zip code
- **Visualisation** — bar charts, histograms and count plots (matplotlib / seaborn) to make the distributions easy to read at a glance

## Tech stack

- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## How to run

```bash
git clone https://github.com/midhulms/Project_Occupation_data.git
cd Project_Occupation_data
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook "Occupation Data.ipynb"
```

## Why this project

A compact, self-contained EDA exercise: no external APIs, no heavy pipeline — just clean pandas work and clear visual storytelling from a single CSV. It's one of the smaller pieces in a broader portfolio spanning BI dashboards (Power BI), applied regression (Enterprise AI Adoption analysis) and an agentic LLM cost router.

## Author

**Midhul Manoharan Nair Sobha Kumar**
Business Analyst / Data Analyst — Paris, France
[LinkedIn](https://linkedin.com/in/midhulms) · [Portfolio](https://midhulms.github.io) · midhulmsofficial@gmail.com

---
*Note: this README was drafted from the repo's file structure and column headers (the notebook's exact cell-by-cell output couldn't be pulled through automated fetch). If any specific chart or finding described above doesn't match what's actually in the notebook, let me know and I'll adjust it.*
