# DSA2040A_ETL_Midterm_Ted_340
#  MIDSEM EXAM

##  Project Overview
This project demonstrates an ETL pipeline using Python. It extracts customer transaction data, transforms it through cleaning, enrichment, and structural improvements, and loads it into structured formats (SQLite) for analytics use.

##  ETL Phases

### Extract (`etl_extract.ipynb`)
- Loading raw and incremental datasets and displaying the top rows
- Showing data structure, types, and missing values


### Transform (`etl_transform.ipynb`)
 - Removed duplicates and handled missing values
 - Converted date columns to datetime
 - Added a `total_price` column by calculating 'unit_price' * ' quantity'
 - Created customer tiers (Bronze, Silver, Gold)
 - Saved transformed datasets

### Load (`etl_load.ipynb`)
- Loaded cleaned data into SQLite databases
- Previewed data with queries and `.head()` outputs

##  Tools Used
- Python
- Jupyter Notebook
- SQLite
- Git and GitHub

##  How to Run the Project

1. Copy this repo:
git clone https://github.com/tk2814/DSA2040A_ETL_Midterm_Ted_340.git
cd DSA2040A_ETL_Midterm_Ted_340

2. Open and run each notebook in order:
- `etl_extract.ipynb`
- `etl_transform.ipynb`
- `etl_load.ipynb`

3. View final data in `/loaded/` folder.



![Screenshot 2025-06-24 201537](https://github.com/user-attachments/assets/f4165aae-74ac-4966-b643-bceec8848e8b)
