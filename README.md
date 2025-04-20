# Automated-Financial-Data-Extraction-Power-BI-Dashboard

## Description
Automates financial data extraction from Outlook emails, stores attachments in Google Drive, fetches data using a Python API, and updates dynamic Power BI dashboards. Enables real-time insights into credit scores and loan eligibility.

## Technologies Used
- Microsoft Outlook
- Power Automate
- Google Drive
- Google Cloud Services (GCP)
- Python
- Power BI
- API Integration

## Features
- Automatically extract and download email attachments containing credit scores
- Store files securely in Google Drive
- Use Python API to fetch and load new files into Power BI
- Real-time dashboards with credit and financial insights
- Custom columns and metrics using Power Query (M Code) and DAX
- Evaluate loan eligibility and potential customers

## Folder Structure
📄 credentials_sample.json         # Sample GCP credentials
📁 Dashboard_Overview              # Power BI dashboard screenshots
📄 M_code.txt                      # M Code used in Power Query
📄 Dax_code.txt                    # DAX formulas for data analysis
📄 Financial Dataset Code.ipynb    # Python code to fetch files from Google Drive
📄 README.md

## How to Use
- Clone this repository.
- Create a Power Automate rule to filter emails with "Credit Score" in the subject or body.
- Automatically download and store attachments in Google Drive.
- Set up a GCP service account and download the credentials JSON.
- Rename it as credentials_sample.json and place it in the project folder.
- Open Power BI and use the Python script (from .ipynb or .py) in Power Query to load files from Google Drive.
- Dashboards update dynamically with new data.

## Dashboard Screenshots
Found in Dashboard_Overview/:
Dashboard_Page_1.jpg
Dashboard_Page_2.jpg

## DAX & M Code References
- M_code.txt: Contains Power Query logic for transformations.
- Dax_code.txt: Includes calculations for:
Loan type classification
Average credit inquiries
LTV score
Potential customer analysis

## Author
Trushant Jagdish
