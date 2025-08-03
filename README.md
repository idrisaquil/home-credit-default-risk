This project tackles the critical business need of predicting loan repayment at Home Credit. The core objective is to leverage historical loan application data and build a robust AI model that can accurately predict whether an applicant will be able to repay their loan. 

The Challenge
Many individuals face difficulties securing loans due to limited or non-existent credit histories. Home Credit aims to address this challenge by broadening financial inclusion for the unbanked population through providing positive and safe borrowing experiences. To achieve this, Home Credit relies on various alternative data sources, including telecommunication and transactional information, to assess repayment abilities. The challenge lies in developing a model that can effectively utilize this data to identify potential defaulters while ensuring that creditworthy individuals are not unfairly rejected. 

The data
Home Credit has provided a comprehensive dataset to facilitate the development of predictive models. The dataset consists of several relational tables containing a wide range of information about applicants, including: 
Static applicant data: Gender, age, number of family members, occupation, housing information (e.g., fence material, square footage), education, etc.

Previous credit history: Information from other financial institutions (bureau data) and Home Credit itself (previous applications data).
Monthly data: Monthly information about previous credit and cash loans, including payment history, credit card balance data, and installment payments. 

It is important to note that the dataset exhibits a class imbalance, with a significantly higher number of loans being repaid on time compared to loans experiencing repayment difficulties.
