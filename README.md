# Lending Club Case Study
The primary goal of this exploratory data analysis (EDA) case study is to identify the key factors and patterns that drive loan defaults, with a specific focus on distinguishing between loans that are "Fully Paid" and those that are "Charged Off."

The dataset contains the complete loan data for all loans issued through the time period 2007 to 2011.
### Understanding Loan Status and Data Limitations
The loan dataset includes a loan_status column, which categorizes loans into three states:
- Fully Paid: The borrower has successfully repaid the loan in full.
- Charged Off: The loan has been deemed uncollectible and is considered a loss for the lender (default).
- Current: The borrower is currently making payments, and the loan is in good standing.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

By focusing on loans with definitive outcomes ("Fully Paid" or "Charged Off"), we aim to uncover patterns and relationships that can help business:
- Identify High-Risk Borrowers: Determine the borrower characteristics, loan attributes, and credit history factors that are strong predictors of loan defaults.
- Inform Lending Decisions: Use the insights from EDA to refine lending policies, adjust interest rates based on risk, and develop more effective underwriting criteria.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  > We work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- What is the background of your project?
  > This project is done as part of IIITB ML & AI PGDM programme. This case study will judge us on Exploratory Data Analysis.
- What is the business probem that your project is trying to solve?
  > The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- What is the dataset that is being used?
  > Loan.csv - The data contains information about past loan applicants and whether they 'defaulted' or not. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Inquiries in Last 6 Months: Charged-off loans have median number of inquiries in the past 6 months equivalent to 75% of the paid off loans. This indicates that those borrowers are likely to default for whom more number of inquiries were done.
- Address State - As we noticed, Nebraska state had the maximum number of defaulters. We can take the address state into consideration while assessing borrowers from next time.
- Term - Borrowers with 60 month term tends to default more. It can be because more time to pay off a loan increases the chance of them charging off.
- Annual Income: The median annual income for fully paid loans is slightly higher than for charged-off loans. However, there's considerable overlap in the distributions, and both groups have a wide range of incomes.
- Interest Rate: 25 percentile of charged off loans have approximately the same interest rate as the median of paid off loans. This indicates that loans with higher interest rate are very likely to being charged off. Charged-off loans have a significantly higher median interest rate compared to fully paid loans.
- Purpose - "Small business" loans exhibit the highest default rate, followed by "renewable_energy" and "Educational". Car, Credit card, Major purchase and Wedding have lower default rates.
- Home Ownership - "Other" categories have higher default rates compared to others. The ways to verify home ownership of a borrower can be improved.
- Grade - As the grade moves from A to G, credit worthiness decreases and risk factor increases. It also leads to increase in default rate. There are still default borrowers with grade A. This variable’s calculation can be improved.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3+
  - numpy
  - pandas
  - matplotlib
    - pyplot
    - gridspec
  - seaborn
  - warnings

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by upGrad IIITB ML & AI PGDM programme.
- This project was based on EDA.


## Contact
Created by [@tallbrat] [@Shaily20] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
