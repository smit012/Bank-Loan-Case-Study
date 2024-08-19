# Bank-Loan-Case-Study
Advance_Excel
<br>

_______________________________________________________________________________________________________________________________________________________________________________________
### DATA_SET : https://drive.google.com/drive/folders/1_q9XTVBPBG4gIPUPL6SingvJyhj690kb

### Important_Note :https://docs.google.com/document/d/1x1B851YFrNM9Zv5Jk0YuBMFcE0nIvq_F/edit?usp=sharing&ouid=101497979566065047806&rtpof=true&sd=true
<HR>
<br>

## Analysis part In Excel 

- **Note**: The Excel file is quite large, approximately 90MB. Therefore, I've provided a link to both the Excel sheet and a Google Sheet. Please download them and review the content.
  
**1) Excel :** https://onedrive.live.com/view.aspx?resid=42DDA65A1592569B%21141418&authkey=!AK2aqE91vl57oJs
  
**2) Google_Sheet :** https://drive.google.com/file/d/1jiD5BH37p9i423J93nGrpyMo0HfQxJlb/view
<br>
<hr>

# Description :

Description:
Imagine you're a data analyst at a finance company that specializes in lending various types of loans to urban customers. Your company faces a challenge: some customers who don't have a sufficient credit history take advantage of this and default on their loans. Your task is to use Exploratory Data Analysis (EDA) to analyze patterns in the data and ensure that capable applicants are not rejected.

### **When a customer applies for a loan, your company faces two risks:**

1) If the applicant can repay the loan but is not approved, the company loses business.

2) If the applicant cannot repay the loan and is approved, the company faces a financial loss.

The dataset you'll be working with contains information about loan applications. It includes two types of scenarios:

1) **Customers with payment difficulties**: These are customers who had a late payment of more than X days on at least one of the first Y installments of the loan.

2) **All other cases**: These are cases where the payment was made on time.

### **When a customer applies for a loan, there are four possible outcomes:**

**Approved:** The company has approved the loan application.

**Cancelled:** The customer cancelled the application during the approval process.

**Refused:** The company rejected the loan.

**Unused Offer:** The loan was approved but the customer did not use it.


_**Your goal in this project is to use EDA to understand how customer attributes and loan attributes influence the likelihood of default.**_

### **Business Objectives:**
The main aim of this project is to identify patterns that indicate if a customer will have difficulty paying their installments. This information can be used to make decisions such as denying the loan, reducing the amount of loan, or lending at a higher interest rate to risky applicants. The company wants to understand the key factors behind loan default so it can make better decisions about loan approval.

**Note:** To better understand this project, you might want to research a bit about risk analytics in banking and financial services. Understanding the types of variables and their significance should be enough.

<br>
<hr>

## Data Analytics Tasks

This repository contains various data analytics tasks performed using Excel. The tasks focus on identifying missing data, detecting outliers, analyzing data imbalance, performing univariate and bivariate analysis, and identifying top correlations.


## Tasks Overview

### 1. Identify Missing Data and Handle It Appropriately

**Objective**:  
Ensure accuracy by identifying and handling missing data.

**Task**:  
As a data analyst, you come across missing data in the loan application dataset. It is essential to handle missing data effectively to ensure the accuracy of the analysis.

- Identify the missing data in the dataset using Excel built-in functions like `COUNT`, `ISBLANK`, and `IF`.
- Decide on an appropriate method to deal with missing data, considering using functions like `AVERAGE` or `MEDIAN` for imputation or other appropriate methods available in Excel.

**Visualization**:  
Bar chart showing the proportion of missing values.

**Graph Suggestion**:  
Create a bar chart or column chart to visualize the proportion of missing values for each variable.

---

### 2. Identify Outliers in the Dataset

**Objective**:  
Detect and handle outliers to prevent distortion in analysis.

**Task**:  
Outliers can significantly impact the analysis and distort the results. You need to identify outliers in the loan application dataset.

- Detect and identify outliers using Excel statistical functions and features, focusing on numerical variables.
- Utilize Excel functions like `QUARTILE`, `IQR`, and conditional formatting to identify potential outliers. Consider applying thresholds or business rules to determine if the outliers are valid data points or require further investigation.


**Visualization**:  
Box plot highlighting outliers.

**Graph Suggestion**:  
Create box plots or scatter plots to visualize the distribution of numerical variables and highlight the outliers.

---

### 3. Analyze Data Imbalance

**Objective**:  
Understand data distribution for reliable model building.

**Task**:  
Data imbalance can affect the accuracy of the analysis, especially for binary classification problems. Understanding the data distribution is crucial for building reliable models.

- Determine if there is data imbalance in the loan application dataset.
- Calculate the ratio of data imbalance using Excel functions like `COUNTIF` and `SUM` to calculate the proportions of each class. Compare the class frequencies to assess data imbalance.


**Visualization**:  
Pie chart showing class distribution.

**Graph Suggestion**:  
Create a pie chart or bar chart to visualize the distribution of the target variable and highlight the class imbalance.

---

### 4. Perform Univariate, Segmented Univariate, and Bivariate Analysis

**Objective**:  
Gain insights into loan default factors.

**Task**:  
To gain insights into the driving factors of loan default, it is important to conduct various analyses on consumer and loan attributes.

- Perform univariate analysis to understand the distribution of individual variables.
- Perform segmented univariate analysis to compare variable distributions for different scenarios.
- Perform bivariate analysis to explore relationships between variables and the target variable using Excel functions and features.

**Visualization**:  
Various charts, including histograms and scatter plots.

**Graph Suggestions**:  
- Create histograms, bar charts, or box plots to visualize the distributions of variables.
- Create stacked bar charts or grouped bar charts to compare variable distributions across different scenarios.
- Create scatter plots or heatmaps to visualize the relationships between variables and the target variable.

**Hint**:  
Utilize Excel functions like `COUNT`, `AVERAGE`, `MEDIAN`, and statistical functions for descriptive analysis. Utilize Excel features like filters, sorting, and pivot tables for segmented and bivariate analysis.

---

### 5. Identify Top Correlations for Different Scenarios

**Objective**:  
Identify strong indicators of loan default.

**Task**:  
Understanding the correlation between variables and the target variable can provide insights into strong indicators of loan default.

- Segment the dataset based on different scenarios (e.g., clients with payment difficulties and all other cases).
- Identify the top correlations for each segmented data using Excel functions like `CORREL`.

**Visualization**:  
Heatmap showing top correlations.

**Graph Suggestion**:  
Create correlation matrices or heatmaps to visualize the correlations between variables within each segment. Highlight the top correlated variables for each scenario using different colors or shading.

---


## Contact

For any questions, feel free to reach out to https://www.linkedin.com/in/smit-surani-140a58244/ .



_________________________________________________________________________________________________________________________________________________________________________________________


