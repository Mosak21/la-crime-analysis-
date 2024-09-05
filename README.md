# Los Angeles Crime Data Analysis Project

## Overview

This repository contains an analysis project on **Los Angeles Crime Data**. The dataset provided is a modified version of the public data available from **Los Angeles Open Data**. The project aims to support the **Los Angeles Police Department (LAPD)** by identifying patterns in criminal behavior, which can be used to allocate resources more effectively across the city. 

## Dataset Information

The dataset `crimes.csv` contains records of crimes reported in **Los Angeles**, including details about the crime type, victim, location, and more. Below is a summary of the key columns in the dataset:

| Column         | Description |
|----------------|-------------|
| `DR_NO`        | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits. |
| `Date Rptd`    | Date reported - MM/DD/YYYY. |
| `DATE OCC`     | Date of occurrence - MM/DD/YYYY. |
| `TIME OCC`     | Time of occurrence in 24-hour military format. |
| `AREA NAME`    | Geographic Areas or Patrol Divisions responsible for the crime location. |
| `Crm Cd Desc`  | Crime description. |
| `Vict Age`     | Victim's age. |
| `Vict Sex`     | Victim's gender (F: Female, M: Male, X: Unknown). |
| `Vict Descent` | Victim's ethnic descent. |
| `Weapon Desc`  | Description of the weapon used, if applicable. |
| `Status Desc`  | Crime status. |
| `LOCATION`     | Street address where the crime occurred. |

## Objectives

This project will focus on the following key objectives:
1. **Crime Distribution**: Analyze the distribution of crimes across different neighborhoods and times.
2. **Crime Trends**: Identify any time-based trends in the occurrence of specific types of crimes.
3. **Victim Demographics**: Analyze victim demographics such as age, gender, and descent to understand the populations most affected by crime.
4. **Weapon Use**: Investigate the prevalence of weapons in reported crimes.

## Installation

To run this project, clone the repository and install the required Python libraries:

```bash
git clone https://github.com/your-username/la-crime-analysis.git
pip install pandas matplotlib seaborn
```

## Running the Analysis

Once the dependencies are installed, load the dataset and start exploring the data using the provided Jupyter notebook (`crime_analysis.ipynb`).

```python
import pandas as pd
df = pd.read_csv('data/crimes.csv')
```

## Features

- **Exploratory Data Analysis (EDA)**: Gain insights into the overall crime landscape in Los Angeles.
- **Visualization**: Use plots and charts to present crime patterns by area, type, and time.
- **Resource Allocation Recommendations**: Based on the analysis, suggest areas where resources should be concentrated.

## Contributing

If you want to contribute to this project, feel free to fork the repository, submit issues, or create pull requests.

---

