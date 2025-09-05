# COVID-19 Clinical Trials EDA  
[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-latest-blue)](https://pandas.pydata.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-latest-orange)](https://matplotlib.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-latest-purple)](https://seaborn.pydata.org/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Overview
The COVID-19 Clinical Trials EDA notebook is a comprehensive tool for analyzing and visualizing clinical trials data. It provides insights into:

- Trial distribution by status, phase, type, interventions, and sponsors  
- Enrollment patterns and outlier detection  
- Trends over time by registration or start date  
- Top interventions, sponsors, and countries involved in trials  

This project is built using Python, Pandas, Matplotlib, Seaborn, and Excel export for reproducible reporting.

---

## Features

**Data Summary:**  
- Displays dataset shape, types, missingness, and basic numeric summaries  

**Univariate Analysis:**  
- Recruitment status distribution  
- Phase distribution  
- Study type distribution  
- Top interventions  
- Countries and sponsors frequency  
- Enrollment distribution  

**Bivariate Analysis:**  
- Enrollment vs Phase  
- Enrollment vs Status  
- Trends of trials over time  

**Advanced Analysis:**  
- Intervention timelines  
- Top trials by enrollment  
- Sponsor class categorization (Academic / Industry / Government / Other)  

**Export:**  
- Excel report with summary tables  
- Figures saved as PNG  

---

## Installation

Clone the repository:  

```bash
git clone git@github.com:PanchangniDhangar/covid19-trials-eda.git
cd covid19-trials-eda
```
Install dependencies:

```bash
pip install -r requirements.txt
```
## Required Packages

- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) / [xlsxwriter](https://xlsxwriter.readthedocs.io/)

Usage
Ensure your data file COVID clinical trials.csv is in the project directory.

Run the analysis notebook (Jupyter recommended):

```bash
jupyter notebook COVID_Trials_EDA.ipynb
```
Open the notebook COVID_Trials_EDA.ipynb and run cells sequentially.

## Data

`COVID clinical trials.csv` contains columns such as:

- **nct_number / trial_id**: Unique trial identifier  
- **title**: Trial title  
- **status**: Recruitment status  
- **phase**: Study phase  
- **study_type**: Interventional / Observational  
- **enrollment**: Planned enrollment  
- **start_date, completion_date**: Dates  
- **country, sponsor, intervention, condition**: Trial details  

The notebook handles normalization, cleaning, and aggregation of this data.

## Visualizations

The notebook produces:

- Status, phase, study type, intervention, sponsor, and country distributions  
- Enrollment histograms (clipped for outliers)  
- Boxplots for enrollment by phase and status  
- Time trends for trial registrations or start dates  
- Intervention timeline plots  
- Sponsor class distribution  

All figures are saved in the `figures` folder.

## Screenshots

<img width="1184" height="584" alt="output" src="https://github.com/user-attachments/assets/8f28aa4a-17fa-4e1c-aae6-a35bdf05e337" />
<img width="1184" height="584" alt="outp3ut" src="https://github.com/user-attachments/assets/e38340a1-35ae-40f5-98db-044d7b54acbd" />
<img width="1184" height="584" alt="out4ut" src="https://github.com/user-attachments/assets/a0d7b8f0-f293-47d2-9bd6-c88b0794696d" />
<img width="1184" height="584" alt="out2put" src="https://github.com/user-attachments/assets/087c52be-9b25-4278-820a-7a426636c7af" />

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please submit pull requests or open issues for bugs, feature requests, or improvements.

## Contact

For any questions or support, reach out to Panchangni at panchangnidhangar@gmail.com.
