# London Bike Sharing — Regression & Statistical Analysis

## Project summary
This project analyzes [London bike-sharing data](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) to explore distributional differences across segments, test multiple statistical hypotheses with interval estimates, and build and diagnose linear regression models to explain and predict bike rental counts.

## What was done
- Performed exploratory data analysis and distributional comparisons (KDEs, boxplots).
- Quantified distribution shifts using **PSI** and **Kolmogorov–Smirnov (KS)** tests.
- Tested segment differences (e.g., summer vs. winter) with bootstrap interval estimation and nonparametric tests (Mann–Whitney).
- Tested variance differences (e.g., wind variability) with bootstrap and **Levene** test.
- Built OLS regression models (several specifications), diagnosed Gauss–Markov assumptions (Breusch–Pagan test for heteroskedasticity, residuals Q–Q plot) and multicollinearity (VIF).
- Applied corrective steps (feature selection, outlier removal) and compared intermediate vs. final models using $Adj. \; R^2$ and diagnostic metrics.
- Produced interactive and static visualizations (Plotly + Matplotlib/Seaborn) to illustrate key findings and support interpretation.
- Formulated product hypotheses and practical experiment ideas based on statistical findings.

## Technologies & libraries
- Language / environment: **Python**, **Jupyter Notebook**
- Data processing: **pandas**, **numpy**
- Statistics & modeling: **scipy**, **statsmodels**, **scikit-learn**
- Visualization: **matplotlib**, **seaborn**, **plotly**
- Utilities: bootstrap via numpy, VIF from statsmodels
