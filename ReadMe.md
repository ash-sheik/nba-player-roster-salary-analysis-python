# NBA Player Roster and Salary Analysis | Python

An exploratory Python notebook analyzing NBA player team distribution, positions, age and recorded salary patterns.

## Analysis questions

- How are players distributed across teams?
- Which positions are most common?
- What does the age distribution look like?
- How do recorded salary totals and medians vary by team and position?
- Is age associated with recorded salary in this dataset?

## Data quality

The included CSV has inconsistent values in the `Height` column, including values formatted like dates. The notebook preserves the raw values and excludes height from quantitative analysis. It does not generate random replacement measurements.

Salary values are converted to numeric form; missing values are excluded from salary summaries and reported. Team salary totals should be interpreted with this missingness in mind.

## Repository contents

- `Python-project.ipynb` — revised NBA player analysis notebook.
- `myexcel.csv` — source dataset currently included in the repository.
- `Output _graphs/` — charts from the earlier notebook run; these are not yet refreshed against the revised notebook and should not be treated as current results.

## Run locally

Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch Jupyter from the repository directory:

```bash
jupyter notebook
```

Open `Python-project.ipynb` and run all cells in order.

## Before using as a portfolio project

1. Confirm and document the original dataset source, snapshot date and license.
2. Re-run the notebook locally and regenerate the charts in `Output _graphs/`.
4. Add a concise findings section based on the fresh notebook outputs.

## Author

Ashiba B

[LinkedIn](https://www.linkedin.com/in/ashiba-data-analyst) · [GitHub](https://github.com/ash-sheik)
