# Notebook and data boundaries

## Repository layout

| Artifact | Current responsibility |
| --- | --- |
| `StatsModels.ipynb` | Narrative exploratory analysis, plots, correlation discussion, OLS fitting, and saved cell outputs. |
| `dataset.csv` | Local tabular input used by the notebook. |

## Analysis flow

1. The notebook loads the CSV using pandas.
2. It reviews shape, columns, sample values, types, and descriptive statistics.
3. It plots rental-value distribution and explores correlations.
4. It uses area as an explanatory variable for a simple Statsmodels OLS rental-value model.
5. It discusses the resulting fit and cautions that correlation does not establish causation.

## Interpretation boundary

The reported notebook results describe one historical execution against the committed CSV. They do not prove generalization, causality, fair outcomes, or suitability for a specific market. An R-squared result alone is insufficient for pricing use; the notebook does not establish a holdout evaluation, residual diagnostics, data representativeness, or live-rate applicability.

## Data boundary

The repository contains no documented dataset source or license. Treat the CSV as internal learning material until provenance and permitted use are verified. Do not publish, combine, or use it for decision-making based solely on this repository.
