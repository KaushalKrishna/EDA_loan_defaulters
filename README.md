# `EDA` to identify defaulters

The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a __defaulter__. 

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is __likely__ to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is __not likely__ to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios(The categories in our `Target` variable):

- __The client with payment difficulties:__ he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,

- __All other cases:__ All other cases when the payment is paid on time.

In this case study, we will use __EDA__ to understand how consumer attributes and loan attributes influence the tendency of default.

## Business Objective

This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study.


project file - `eda_defaulters.ipynb`


Note: since the datsets are too huge, they have been uploaded in gdrive (https://drive.google.com/drive/folders/1GS60lYxJheXqIYr9dkZFwR7lzvlvDfTp?usp=sharing)
