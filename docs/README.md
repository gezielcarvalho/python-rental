# Current-state documentation

## Purpose

This repository is a notebook-based learning exercise in exploratory rental-data analysis with pandas, Matplotlib, Seaborn, and Statsmodels.

## Current state

- Main artifact: `StatsModels.ipynb`.
- Data: `dataset.csv`, containing 3,000 rows and fields for rental value, area, construction year, location/district codes, bathrooms, and kitchens.
- Analysis: inspection, descriptive exploration, distribution/correlation visualizations, and a simple OLS regression focused on area and rental value.
- Environment: the notebook records one historical Python execution version, but no requirements/lockfile/environment specification is committed.
- Quality: no automated tests, CI workflow, data-validation checks, train/test partition, or model-evaluation pipeline was found.
- Data provenance: source, license, collection method, geographic context, and allowed-use conditions are not documented.

## Decision

Keep as a supporting data-analysis learning artifact, not a portfolio flagship or a predictive rental model. It must not inform business or consumer decisions without an approved data-governance and modeling effort.

See the [analysis charter](project-charter.md), [notebook/data boundaries](architecture.md), and [quality handoff](delivery-and-quality.md).
