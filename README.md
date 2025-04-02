# Phonepe_Transaction_Insights

## Overview
With the increasing reliance on digital payment systems like PhonePe, understanding transaction dynamics, user engagement, and insurance-related data is crucial. This project analyzes and visualizes aggregated payment data, maps transaction values at state and district levels, and identifies top-performing regions and users.

##:bar_chart: Approach

### 1. Data Extraction
- Clone the PhonePe transaction data repository.
## 📂Dataset
- **Source**: PhonePe Pulse Data
- **GitHub Repository**: [https://github.com/PhonePe/pulse](https://github.com/PhonePe/pulse)
- Load data into a SQL database.

### 2. SQL Database and Table Creation
#### Aggregated Tables
- `Aggregated_user`: User-related aggregated data.
- `Aggregated_transaction`: Aggregated transaction values.
- `Aggregated_insurance`: Aggregated insurance data.

#### Map Tables
- `Map_user`: Mapping of user data.
- `Map_map`: Transaction values at state/district levels.
- `Map_insurance`: Insurance mapping data.

#### Top Tables
- `Top_user`: Data on top users.
- `Top_map`: Top-performing states, districts, and pin codes.
- `Top_insurance`: Top insurance transaction data.

### 3. Data Analysis Using SQL and Python
- Execute SQL queries for data insights.
- Use Python libraries (Pandas, Matplotlib, Seaborn) for data visualization.
- Create visualizations (bar charts, pie charts) to highlight key findings.

### 4. Dashboard Development
- Develop an interactive dashboard using Streamlit.
- Create dynamic visualizations using Power BI.

## Features
- **Data Extraction:** Loading transaction data from the PhonePe dataset.
- **Database Management:** MySQL database setup and data storage.
- **SQL Analysis:** Querying and analyzing transaction data.
- **Data Visualization:** Matplotlib and Seaborn for graphical representation.
- **Dashboard Development:** Interactive visualization using Streamlit and Power BI.

## Project Structure
```
|-- Phonepe_dataexe.ipynb        # Jupyter Notebook for data analysis and SQL queries
|-- Phonepe_Streamlit.py         # Streamlit application for interactive visualization
|-- Phonepe_Transaction_Insight.pbix  # Power BI dashboard file
|-- README.md                    # Project documentation
```

## Installation
### Prerequisites
- Python 3.8+
- MySQL Server
- Jupyter Notebook
- VS Code
- Power BI/Tableau (for visualization)

## Setting Up the Database
1. Start MySQL Server and create a database:
   ```sql
   CREATE DATABASE phonepe_db;
   ```
2. Import transaction data into MySQL tables.
3. Run SQL queries from `Phonepe_dataexe.ipynb` to analyze the data.

## Dashboard Insights
- **Transaction Trends**: Aggregated transaction data across different timeframes.
- **User Demographics**: Insights into user engagement by geography.
- **Financial Insights**: Analysis of payment patterns and top transactions.

## Running the Streamlit App
To launch the Streamlit dashboard:
```sh
streamlit run Phonepe_Streamlit.py
```

## 🎯 Streamlit output:
- ![Phonepe_Homepg](https://github.com/user-attachments/assets/19df4998-64c9-421c-9cbc-eb2710968d0f)
