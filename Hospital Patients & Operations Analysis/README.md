# Hospital Data Analysis

## Project Overview
This project contains an exploratory data analysis of hospital operations, focusing on admission statistics, room management, and patient stays. By analyzing factors such as the severity of illness, admitting departments, and age distributions, we derive business insights that can assist hospital management in resource allocation and capacity planning.

## Setup and Installation
To run the analysis locally, make sure you have Python 3 and Jupyter Notebook installed on your system.

1. Clone or download this project folder.
2. Install the critical dependencies by running:
   ```bash
   pip install pandas matplotlib seaborn jupyter notebook
   ```
3. Navigate into the folder using your command line interface.
4. Launch the Jupyter Notebook interface:
   ```bash
   jupyter notebook
   ```

## Files Included
- **`Hospital_Data_Analysis.ipynb`**: The main Jupyter Notebook. This file contains well-commented Python code ranging from data cleaning to advanced statistical charting.
- **`Hospital Data.csv`**: The primary dataset with 500k hospital stay entries. Due to size limitations, it can be parsed using pandas correctly in chunks or as a whole depending on system memory. [Download](https://github.com/Moiz-Ali-Rajpoot/SQL-Projects/blob/main/Hospital%20Patients%20%26%20Operations%20Insights/Hospital%20Data.csv)
- **`generate_hospital_nb.py`**: A generator script to build the jupyter notebook file automatically using nbformat.

## How to View and Run
Open `Hospital_Data_Analysis.ipynb` via Jupyter Notebook or any compatible IDE (like VSCode). Run the script sequentially from top to bottom to view the data loading methods, visual graphs (such as Boxplots showing Length of Stay vs Severity of Illness), and the resulting business insights.
