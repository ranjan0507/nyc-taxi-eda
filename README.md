### Overview
This project performs a structured exploratory data analysis (EDA) on NYC Yellow Taxi trip records to understand demand patterns, fare behavior, and operational anomalies .

### Dataset
Data files are not included in the repository , please download it from : https://www.kaggle.com/datasets/shayanshahid997/yellow-taxi-trip-record-of-january-2024

Format: parquet

Granularity: One row represnts one taxi trip

### Project Structure
```
nyc-taxi-eda/
│
├── data/
│   └── raw/
│       └── (parquet data)
│
├── notebooks/
│   └── 01_eda_nyc_taxi.ipynb
│
├── README.md

```
Place the data under data/raw/ folder .

### EDA objectives
1. When do taxi trips occur (hourly and weekly demand patterns)?

2. How are fares distributed and what drives fare variability?

3. How does trip distance relate to fare?

4. What data quality issues and anomalies exist?

5. Which features are potentially useful or risky for modeling?

### Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn
