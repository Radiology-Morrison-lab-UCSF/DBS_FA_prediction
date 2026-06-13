# White matter FA predicts DBS medication change in Parkinson's disease

Code and processed data for the manuscript *"White matter fractional anisotropy predicts Parkinson's disease medication changes with deep brain stimulation."*

## Contents
- `FA_DBS_analysis.ipynb` — reproduces all analyses and figures in the paper.
- `DBS_FA_cohort_data.xlsx` — processed cohort data (`data` sheet) with column definitions (`data_dictionary` sheet).

## Data
146 preoperative cases; the notebook restricts to the 143 STN/GPi analytic cohort (VIM cases excluded). One subject is missing parahippocampal cingulum (CGH) FA. no protected health information is included. Units and encodings are in the `data_dictionary` sheet.

## Usage
Python 3.9+ with `numpy`, `pandas`, `scipy`, `scikit-learn`, `matplotlib`, `openpyxl`. Place the xlsx beside the notebook and run all cells. Figures are written to `figures/`.

## Notes
- LASSO stability selection is seeded (`random_state=42`) for reproducibility.

## Licenses

* Copyright 2025 UCSF

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at:
[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

* All code files in this repository are licensed under the Apache License 2.0.
* `Coming soon` were acquired at the University of California San Francisco and are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

## Acknowledgments

This project is part of ongoing research in the Radiology-Morrison-lab-UCSF. Special thanks to all contributors and collaborators involved in this work.
