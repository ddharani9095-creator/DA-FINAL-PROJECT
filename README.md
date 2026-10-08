**Chicago Crime Data Analysis (2023)**
**Description**

This project analyzes 2023 Chicago crime data pulled directly from Google BigQuery's public dataset (bigquery-public-data.chicago_crime.crime). The workflow covers the full analytics pipeline: querying and extracting cloud-hosted data via SQL, cleaning and performing exploratory data analysis (EDA) in Python, and building an interactive Power BI dashboard for visualization. The goal is to uncover patterns in crime type, arrest rates, geographic distribution (by district/ward), and time-based trends (by month, day, and hour), and present these insights through visuals and KPIs. This project was built as part of my portfolio while training in the Entri Elevate AI-Driven Data Analytics program.

**Getting Started**
Dependencies
Python 3.8 or above
Libraries: pandas, NumPy, Matplotlib, Seaborn
Jupyter Notebook or Google Colab
Power BI Desktop
Google Cloud account (for BigQuery access — free tier is sufficient)
Works on Windows 10/11, macOS, or Linux


**Installing**
Clone this repository to your local machine:
  **git clone https://github.com/ddharani9095-creator/chicago-crime-analysis.git**
  
**Install required Python libraries:**

  pip install pandas numpy matplotlib seaborn
  
**Dataset:** query the data directly from BigQuery (query included in /sql/chicago_crime_query.sql) or use the pre-extracted CSV in /data/chicago_crime_2023.csv

**

### Executing Program
* **Step 1 — Extract data:** Run the SQL query in BigQuery console to pull the 2023 crime dataset (or use the provided CSV)
* **Step 2 — Clean & EDA:** Open and run `chicago_crime_eda.ipynb` in Jupyter/Colab to clean nulls, engineer time-based columns, and explore patterns
  ```
  jupyter notebook chicago_crime_eda.ipynb
  ```
* **Step 3 — Dashboard:** Open `chicago_crime_dashboard.pbix` in Power BI Desktop to view the interactive dashboard (map visual, trend lines, crime type breakdown, arrest rate KPI)

## Key Insights
* Breakdown of crime frequency by type (Theft, Battery, Assault, Criminal Damage, Robbery)
* Arrest rate comparison across crime types
* Geographic hotspots by district and ward (map visual)
* Time-based trends: crime by month, day of week, and hour of day

## Help
If BigQuery access requires setup, refer to Google's free-tier documentation, or use the pre-extracted CSV in the `/data` folder to skip the cloud step.

## Authors
Dharani D (Ji)
[GitHub Profile](https://github.com/ddharani9095-creator)

## Version History
* 0.1
    * Initial Release

## Acknowledgments
* Data source: [Google BigQuery Public Datasets – Chicago Crime](https://console.cloud.google.com/marketplace/product/city-of-chicago-public-data/chicago-crime)
* Built as part of the Entri Elevate AI-Driven Data Analytics program (in collaboration with Illinois Tech)


