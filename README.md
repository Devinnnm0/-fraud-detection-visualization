Fraud Detection Visualization
Overview
This project analyzes transaction data to explore how fraud cases are distributed across different merchant types. A grouped countplot is used to highlight differences between fraud and non-fraud transactions across various categories.

Objective
To visualize fraud patterns across merchant types and identify where fraudulent activity is more common, helping inform potential fraud prevention strategies.

Tools Used
Python (Google Colab)

pandas

seaborn

matplotlib

Process
Loaded transaction data from an Excel file.

Inspected the data and identified key variables: merchant_type and label.

Created a grouped countplot to show fraud vs non-fraud transactions by merchant type.

Interpreted insights based on visual trends.

Key Findings
Across all merchant types, non-fraudulent transactions significantly outnumber fraudulent ones, reflecting the typical imbalance seen in fraud detection datasets.

The "others" category showed the highest number of fraudulent transactions compared to other merchant types.

Fraud was present across all merchant types (travel, groceries, electronics, clothing), but the counts were consistently low relative to non-fraud.

These insights suggest that fraud prevention efforts might benefit from closer monitoring of broad merchant categories like "others," where fraud attempts may be harder to detect through traditional category-based filters.

## Visualization
![Fraud vs Non-Fraud Transactions by Merchant Type](Fraud.png)


Files
fraud_detection_visual.ipynb — Full notebook including data loading, visualization, and analysis.

How to Run
Install required Python libraries: pandas, matplotlib, seaborn, openpyxl.

Open the notebook in Google Colab or Jupyter Notebook.

Run all cells sequentially to reproduce the analysis and visualization.

