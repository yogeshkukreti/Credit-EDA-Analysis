# Risk Analytics in Banking and Financial Services Case Study
<hr>

### Introduction
This case study aims to give us an idea of applying EDA in a real business scenario. In this case study, apart from applying the techniques that we have learned in the EDA module, we will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers.

### Business Understanding
The loan-providing companies find it hard to give loans to people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming a defaulters. Suppose we work for a consumer finance company that specializes in lending various types of loans to urban customers. We have to use EDA to analyze the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.


The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:

* <b>The client with payment difficulties:</b> he/she had late payment of more than X days on at least one of the first Y installments of the loan in our sample,

* <b>All other cases</b>: All other cases when the payment is paid on time.

 

When a client applies for a loan, four types of decisions could be taken by the client/company:

* <b>Approved:</b> The Company has approved loan Application

* <b>Cancelled:</b> The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client, he received worse pricing which he did not want.

* <b>Refused:</b> The company had rejected the loan (because the client does not meet their requirements etc).

* <b>Unused offer:</b>  Loan has been canceled by the client but at different stages of the process.

In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency to default.

### Business Objectives
This case study aims to identify patterns that indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables that are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

#### Note: Download the dataset from the link below.  
https://drive.google.com/open?id=16RQztUqCfJOlbooHqYlJrp6Q7iL65uZB
