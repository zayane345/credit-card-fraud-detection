# 🛡️ credit-card-fraud-detection - Spot Fraud Fast on Windows

[![Download](https://img.shields.io/badge/Download-Release%20Page-4B8BBE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zayane345/credit-card-fraud-detection/releases)

## 🚀 Getting Started

This app helps you review card transactions and flag likely fraud cases. It uses a trained XGBoost model and includes a Power BI dashboard for quick analysis.

If you want to run it on Windows, start by visiting the release page and downloading the latest build:

[Visit the release page to download](https://github.com/zayane345/credit-card-fraud-detection/releases)

## 💻 What This App Does

- Checks transaction data for fraud risk
- Uses a machine learning model built for class imbalance
- Shows results in a simple dashboard
- Helps you review patterns in fraud cases
- Supports quick analysis with Power BI reports

## 📦 What You Need

Use a Windows PC with:

- Windows 10 or Windows 11
- At least 4 GB RAM
- 1 GB free disk space
- Internet access for the download
- A file extractor if the release comes as a .zip file

## 📥 Download and Install

1. Open the release page:
   https://github.com/zayane345/credit-card-fraud-detection/releases

2. Find the latest release at the top of the page.

3. Download the file for Windows. It may be a `.zip`, `.exe`, or another packaged file.

4. If the file is zipped, right-click it and select Extract All.

5. Open the extracted folder.

6. If you see an `.exe` file, double-click it to start the app.

7. If you see a folder with app files, open the file named `README`, `run`, or `start` if present.

8. If Windows asks for permission, select Yes.

## 🧭 First Run

When you start the app for the first time:

- Wait for the program to finish loading
- Choose or open the sample data file
- Check the fraud score or flagged transactions
- Open the dashboard if the app includes one
- Review the output table for risk results

## 📊 How to Use the Dashboard

The Power BI dashboard helps you inspect fraud patterns and review transaction trends.

You can use it to:

- See how many cases were marked as fraud
- Compare transaction amounts
- Spot unusual activity by time or category
- Review patterns across groups of transactions

## 🔍 Typical Workflow

1. Start the app
2. Load the transaction data
3. Run the fraud check
4. Review flagged records
5. Open the dashboard for a deeper view
6. Export or save the results if needed

## 🗂️ Example Data Format

The app works best with transaction records that include fields like:

- Transaction amount
- Time of transaction
- Card or account activity
- Location or merchant data
- Fraud label, if you are testing with known results

If you use your own data, keep the file clean and in a common format such as CSV.

## ⚙️ Model Details

This repository uses:

- XGBoost for classification
- SMOTE for handling imbalanced data
- Fraud detection focused on binary classification
- Analytics support through Power BI

The model is tuned for fraud cases, where true fraud is rare compared with normal activity.

## 🧪 Expected Results

After running the app, you may see:

- A fraud risk score
- A list of flagged transactions
- A chart of transaction patterns
- Dashboard views for quick review
- High model performance metrics such as AUC

## 🛠️ Troubleshooting

- If nothing happens when you open the file, check that the download finished fully
- If Windows blocks the file, right-click it and choose Run anyway if you trust the source
- If the app closes at start, try extracting the full release package again
- If the dashboard does not open, make sure Power BI Desktop is installed
- If your data does not load, check the file format and column names

## 📁 Suggested Folder Layout

You may see files like these in the release package:

- `app.exe`
- `model`
- `data`
- `dashboard`
- `README`
- `run.bat`

Keep the files in the same folder unless the release notes say otherwise.

## 🔒 Data Privacy

Use only data you are allowed to review. This app is meant for analysis and testing of fraud detection workflows. Treat payment data with care and store it in a safe location.

## 🧩 Use Cases

- Review suspicious card transactions
- Test fraud detection on sample records
- Explore fraud patterns in Power BI
- Compare machine learning results with business reports
- Study imbalanced fraud data in a simple Windows app

## 📌 Repository Topics

classification, data-science, fintech, fraud-detection, imbalanced-learning, machine-learning, power-bi, python, smote, xgboost

## 📥 Download Again

If you need the latest build, go to the release page here:

[https://github.com/zayane345/credit-card-fraud-detection/releases](https://github.com/zayane345/credit-card-fraud-detection/releases)