# STSCI 5740 Project

## Dataset

This project uses the UCI Machine Learning Repository dataset:

Diabetes 130-US hospitals for years 1999-2008
https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

Raw files used in this repo:

- data/raw/diabetic_data.csv
- data/raw/IDS_mapping.csv

## Workflow

The project workflow is intentionally split into two parts:

1. Analysis workflow in Jupyter Notebook (R)
- Main notebook: STSCI5740_Data.ipynb
- Purpose: load raw CSV data, parse mapping tables, run exploratory analysis and transformations.
- Execution style: run R code interactively cell-by-cell in the notebook.

2. Reporting workflow in Quarto document (QMD)
- Main report: STSCI5740_Proj.qmd
- Purpose: produce the final report artifact (PDF) for submission/presentation.
- The report consumes prepared outputs from the analysis workflow.

## Repository Layout

- STSCI5740_Data.ipynb: R-based analysis notebook.
- STSCI5740_Proj.qmd: Quarto report source.
- data/raw: original source CSV files.
- data/processed: transformed datasets generated during analysis.
- artifacts: derived tables and figures used by the report.
- outputs: rendered report/notebook outputs.

## Typical Run Order

1. Open and run STSCI5740_Data.ipynb from top to bottom.
2. Confirm processed outputs are written to data/processed and artifacts.
3. Render STSCI5740_Proj.qmd to generate the final report in outputs.
