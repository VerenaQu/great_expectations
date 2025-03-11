# Project: Research on data quality frameworks - Great Expectations

# Table of Contents
1. Project info
2. Data
3. Requirements
4. Executing the code / Jupyter Notebooks

# Project info
This project aims to test the Python based open source software Great Expectations and assess how it supports data quality measures using an airline data set.

# Data
The data used for the analysis has been downloaded from Bureau of Transportation Statistics: https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FJE&QO_fu146_anzr=Nv4%20Pn44vr45

Filters set: 
- Month: January
- Year: 2024

Selected columns:
- Departures performed
- Seats
- Passengers
- ...

# Requirements
You should have installed Python along with the libraries pandas and great_expectations.

# Project setup
- Scaffold a new great_expectations directory by initializing great_expectations
- Place raw data files (csv) in created input folder 
- Create new empty suite using the Great Expectation data assistant (parsing input csv)
- Run Jupyter Notebooks in order as listed below


# Executing the code / Jupyter Notebooks

**data_manipulation.ipynb:**
Prepare the dataset.

**create_data_source.ipynb:**
Configure the data context.

**initialize_new_expectation_suite.ipynb:**
Initialize Expectation Suite by setting up the onboarding assistant that suggests expectations based on found data types. Save Expectation Suite draft and build Data Docs to review this draft. 

**edit_and_apply_suite.ipynb:**
Edit Expectation Suite draft by adding expectations or removing suggested ones that are not applicable. Save adjusted Suite, apply validator and build Data Docs with validation results.















