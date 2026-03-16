Visualizing Housing Market Trends: An Analysis of Sale Prices and Features using Tableau :

This project analyzes housing market data to uncover how property features and renovation status influence sale prices. The workflow includes acquiring and validating the dataset, preparing and cleaning the data, and building interactive Tableau dashboards to highlight key trends such as house age distribution, sales by renovation status, and relationships between bedrooms, bathrooms, and property values.
The repository contains dataset summaries, preprocessing scripts, Tableau workbooks, and documentation of insights, making it a complete end‑to‑end data visualization project.


Overview :
This project analyzes housing market data to explore how property features and renovation status influence sale prices. Python was used for dataset exploration and preprocessing, while Tableau will be used for interactive dashboards and storytelling.

Dataset-
- Source: Kaggle – Transformed Housing Data
- File: Housing.csv
- Contains property details such as sale price, year renovated, bedrooms, bathrooms, floors, and house age.
Workflow
- ✅ Data Collection (dataset acquired from Kaggle)
- ✅ Initial Analysis (Colab notebook committed)
- ⬜ Data Preparation (cleaning, calculated fields)
- ⬜ Tableau Visualizations (charts and dashboards)
- ⬜ Storyboard & Insights (publish Tableau story)
Repository Contents
- Data-Analysis.ipynb → Colab notebook with dataset exploration

🧹 Data Cleaning :
- Checked dataset in Tableau for null values using filters.
- Verified numeric vs categorical fields (e.g., Price, Area, Bedrooms, Bathrooms, Furnishing Status).
- Began handling missing values:
- Excluded rows with nulls in critical fields (like Price).
- Replaced nulls in optional fields (e.g., Year Renovated → “Not Renovated”).
- Standardized categorical values (e.g., “yes/no” → “Yes/No”, furnishing status categories aligned).
- Saved cleaned workbook (housing-project.twbx) for further visualization.

📊 Data Visualization :
- Task 1: KPI Metrics
  - Created visualization showing:
  - ✅ Count of Housing Data (total records in dataset)
  - ✅ Average Sale Prices (overall market pricing trend)
  - ✅ Average Area (Basement only) using filters for Basement = Yes
- Task 2: Total Sale by Years Since Renovation
  - Built a bar/line chart showing Sum of Sale Prices grouped by Years Since Renovation.
  - Applied filters to handle non‑renovated houses (Years since Renovation = 0).
  - Added labels and formatting for clarity.

