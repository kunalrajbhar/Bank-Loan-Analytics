# Bank Loan Analytics Project 🏦📊

## 📄 Project Overview
This project focuses on analyzing the loan portfolio of a bank using historical loan data to uncover key insights regarding loan disbursement, repayment behaviors, and borrower profiles. The analysis helps in understanding borrower risk, loan performance, and identifying growth opportunities in high-performing regions. We used **Excel**, **Tableau**, **PowerBI**, and **MySQL** to perform the analysis and create interactive dashboards.

---

## ⚙️ KPIs Analyzed

### 1. **Year-wise Loan Amount Stats**
- **Metric**: Total loan disbursement across different years.
- **Key Insight**: The highest loan disbursement was recorded in **2011**, totaling **$260.51M**, showcasing rapid growth compared to previous years, with only **$14.39M** in 2009 and **$46.44M** in 2010.

### 2. **Grade and Sub-grade-wise Revolving Balance**
- **Metric**: Revolving balance distribution across different loan grades and sub-grades.
- **Key Insight**: Sub-grades **B4** and **B5** have the highest revolving balances at around **$35M**, while sub-grade **E5** has the lowest revolving balance at **$9M**.

### 3. **Total Payment for Verified vs Non-Verified Borrowers**
- **Metric**: Comparison of total payment amounts between verified and non-verified borrowers.
- **Key Insight**: Verified borrowers account for **58.88%** of the total payment (**$219.89M**), while non-verified borrowers contribute **41.12%** (**$153.54M**). Verified borrowers show stronger repayment behavior.

### 4. **State-wise and Month-wise Loan Status**
- **Metric**: Loan distribution by state and month.
- **Key Insight**: **California** leads with the highest number of loans at **5.36K**, followed by **New York** with **2.85K**. Other states like **Florida** and **Texas** show moderate loan volumes. Month-wise data reveals potential seasonal borrowing trends.

### 5. **Home Ownership vs Last Payment Date Stats**
- **Metric**: Repayment behavior based on home ownership status.
- **Key Insight**: Borrowers with **mortgages** show the highest repayment amounts, particularly around 2014, while renters and those without home ownership exhibit lower repayment volumes.

---

## 🔍 Insights & Recommendations

1. **Verified Borrowers**: Since verified borrowers contribute the majority of total payments, focusing on encouraging verification processes could reduce risk and enhance loan recovery rates.
   
2. **Revolving Balance**: Grades **B4** and **B5** exhibit the highest revolving balances. Offering better credit terms or tailored loan products to this segment may increase profitability.

3. **Home Ownership**: Mortgage holders demonstrate more reliable repayment behavior, making them a key target group for low-risk lending.

4. **Regional Focus**: **California** and **New York** are high-volume loan regions. Targeting these states with customized loan offerings can drive further growth.

5. **Loan Growth**: The significant loan growth seen in **2011** provides an opportunity to analyze factors that contributed to this spike and replicate successful strategies in future years.

---

## 🛠️ Tools & Technologies Used

- **MySQL**: For data extraction and querying to calculate KPIs and prepare datasets.
- **Excel**: For data cleaning, transformation, and preliminary analysis.
- **PowerBI**: For building interactive dashboards to visualize loan performance and borrower demographics.
- **Tableau**: For creating advanced visualizations that highlight trends in loan disbursement, payment behavior, and borrower risk profiles.

---

## 📊 Data Visualizations
The project includes dashboards and visualizations to present the key insights:

- **Excel Dashboard**: Visualizes loan amounts and basic loan metrics.
- **Tableau Dashboard**: Displays detailed KPIs such as state-wise and grade-wise loan distribution.
- **PowerBI Dashboard**: Interactive reports that showcase loan status, repayment patterns, and borrower segmentation.

---

## 📂 Project Structure

```plaintext
├── data
│   └── finance1.csv               # Loan-level data containing loan amounts, interest rates, and borrower information.
│   └── finance2.xlsx               # Additional data containing borrower credit behavior such as revolving balance and annual income.
├── dashboards
│   └── Bank Analytics Project (Group-6).xlsx        # Excel file with key visualizations.
│   └── Bank Analytics Project (Group-6).twbx      # Tableau workbook for visualizations.
│   └── Bank Analytics Project (Group-6).pbix      # PowerBI file with interactive reports.
├── queries
│   └── Bank Analytics Project (Group-6).sql       # MySQL scripts for data extraction and querying.
├── README.md                       # Project documentation.
└── results
    └── Bank Analytics Project (Group-6).pptx # Final ppt containing insights and recommendations.
