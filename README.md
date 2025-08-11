Electric Vehicle Sales & AQI Analysis
📌 Overview
This project analyzes Electric Vehicle (EV) sales data across Indian states, exploring trends, seasonal patterns, and the relationship between EV adoption and Air Quality Index (AQI) levels.
It includes:

Data preprocessing & cleaning (Jupyter Notebook)

Interactive visual analytics (Power BI dashboard)

Final dataset ready for analysis

📂 Project Files
final.csv → Cleaned dataset with 96,845 rows and 10 columns:

Year — Year of record

Month_Name — Month name

Date — Full date of record

State — State/UT name

Vehicle_Class — Classification of the vehicle

Vehicle_Category — Category (e.g., two-wheeler, four-wheeler)

Vehicle_Type — Specific type of vehicle

EV_Sales_Quantity — Number of EV units sold

AQI — Air Quality Index value

Quarter — Financial quarter

draft.ipynb → Jupyter Notebook containing:

Data cleaning steps (null handling, data type fixes)

Exploratory Data Analysis (EDA) with Python (pandas, matplotlib, seaborn)

Trend and correlation analysis between EV sales and AQI

ev.pbix → Power BI file with:

State-wise EV sales maps

Yearly and monthly sales trends

AQI vs EV adoption comparison

Top-performing states dashboard

🚀 How to Use
1. View the Dataset
Open final.csv in Excel, Power BI, or any CSV viewer to explore the raw cleaned data.

2. Run the Notebook
Open draft.ipynb in Jupyter Notebook or VS Code with Python support.

Install required libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Run all cells to reproduce the analysis.

3. Explore the Dashboard
Open ev.pbix in Power BI Desktop.

Refresh visuals if needed to link with the dataset.

Interact with slicers, filters, and charts to explore insights.

📊 Key Insights (Example Highlights)
EV sales have shown consistent growth in multiple states from 2014–2024.

Some states with high EV adoption also show a decline in AQI values, suggesting potential environmental benefits.

Seasonal peaks in EV sales align with festive and financial year-end periods.

🛠️ Tools & Technologies
Python — Data preprocessing & EDA

Pandas, Matplotlib, Seaborn — Analytics & Visualization

Power BI — Interactive dashboards

CSV — Final structured dataset
📷 Visual Examples
DASHBOARD powerbi
<img width="1328" height="745" alt="image" src="https://github.com/user-attachments/assets/44ade5e3-9f21-4cba-95d4-b1b5e2e3ea7b" />

<img width="1323" height="748" alt="ima<img width="846" height="468" alt="ecae034c-6ef0-4e63-901c-2170adebbfc9" src="https://github.com/user-attachments/assets/6ac75638-b2bf-4628-b5b5-14aedcce1a0c" />
ge" src="https://github.com/user-attachments/assets/a702b4ef-bcc3-4ad8-93e1-7991a5e01eeb" />

<img width="695" height="468" alt="bc315562-d0c2-4f33-8d9a-b06ebd27e628" src="https://github.com/user-attachments/assets/8fdc98c5-fda9-4c2c-b1b6-801f3e21ed2a" />
