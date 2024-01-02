DataSet Link :
[
](https://drive.google.com/drive/folders/14EspBRIDwx1naCabw9h9X9tlSm2wXdk5?usp=share_link) 

Dataset has 3 files as explained below: 
1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.
 
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused or Unused offer.
 
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.



Introduction:
This project aims to provide hands-on experience in applying Exploratory Data Analysis (EDA) techniques within a real business context. In addition to utilizing the EDA skills acquired during the module, the objective is to foster a fundamental understanding of risk analytics in the banking and financial services sector. The focus is on comprehending how data is employed to mitigate the risk of financial loss while extending loans to customers.

Business Context:
Loan providers often face challenges when granting loans to individuals with insufficient or non-existent credit histories. Some consumers exploit this situation by defaulting on loans. Imagine working for a consumer finance company specializing in lending various types of loans to urban customers. The task is to employ EDA to analyze patterns in the data, ensuring that applicants capable of repaying the loan are not unfairly rejected.

Decision Risks:
When assessing loan applications, the company must make decisions based on the applicant's profile. Two types of risks are associated with these decisions:
1. Approving a loan for an applicant likely to repay avoids loss of business for the company.
2. Approving a loan for an applicant likely to default may lead to financial loss for the company.

Data Scenarios:
The provided data includes information about loan applications at the time of applying. It categorizes applicants into two scenarios:
1. Clients with payment difficulties: Individuals with late payments more than X days on at least one of the first Y instalments of the loan.
2. All other cases: Instances where payments are made on time.

Decision Types:
There are four potential decisions that can be made during the loan application process:
1. Approved: The company approves the loan application.
2. Cancelled: The client cancels the application during approval, either due to a change of mind or receiving unfavorable pricing.
3. Refused: The company rejects the loan application based on various criteria.
4. Unused offer: The client cancels the loan at different stages of the process.

Throughout this case study, EDA will be employed to explore how consumer attributes and loan characteristics influence the likelihood of default.

