# NBA Player Roster and Salary Exploration | Python

> **Repository status:** This project is being corrected. The included CSV contains NBA player roster data, not employee workforce records. The repository name and notebook title have not yet been renamed.

This notebook explores a player dataset with team, position, age, height, weight, college and salary fields.

## Dataset and scope

- File: `myexcel.csv`
- Subject: NBA player roster information
- The data includes team and player attributes, with some missing and inconsistently formatted values.
- Verify the original dataset source and license before redistributing or relying on the data.

## Intended analysis

- Player counts by team.
- Roster composition by position.
- Age distribution.
- Salary distribution by team and position.
- Team-level salary expenditure.
- Highest-paid players, subject to data quality checks.

## Important data-quality warning

The source `Height` column contains mixed formats and malformed values. The earlier notebook replaces height values with randomly generated numbers. Randomly generated replacement values are fabricated and are not valid measurements.

**Do not use the notebook's current height-based results as factual findings.** A corrected analysis should preserve the original column, parse valid measurements, flag invalid values as missing and document the treatment. It should not invent replacement heights.

## Repository contents

- `Python-project.ipynb` — existing exploratory notebook; requires correction.
- `myexcel.csv` — dataset used by the notebook.
- `Output _graphs/` — previously generated charts; review before reuse.

## Run locally

Install the common analysis dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open `Python-project.ipynb` in Jupyter or VS Code and run cells in order. Some current notebook outputs reflect the preprocessing issue described above.

## Before presenting this as a portfolio project

1. Rename the repository and notebook to reflect NBA player analysis.
2. Correct height parsing and remove random imputation.
3. Re-run every cell and regenerate all figures.
4. Verify the dataset source and usage terms.
5. Add concise findings supported by the corrected analysis.

## Author

**Ashiba B**
