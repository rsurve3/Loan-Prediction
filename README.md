# Loan-Prediction
Programmed a Logistic Regression Model to predict whether a loan application should be granted based on 11 independent variables by employing Scikit-Learn, Numpy, Pandas, Matplotlib and Seaborn libraries to reduce Non-Performing Loan Ratio from 0.4 to 0.25.

Business Problem
In Q3 2022 results, the top 6 major US banks reported a decline in profits. The underlying reason for this situation was bad loans. Our problem statement focuses on determining whether the applicant can repay the loan sanctioned to them. Specifically, we will leverage various customer demographics and details to accurately determine whether the bank will profit from giving the loan to the said applicant or not. We are trying to address this problem on the bank's behalf. Once model is completed, it will be used as a prototype to showcase to various banks as a representation of how they can profit if they allow us to use our model on their data. 

We are utilizing historical information of loan applicants over a course of 6 months of US banks extracted from GitHub. The dataset contains several applicant attributes such as demographics, salary, loan terms, credit rating, etc. After data processing, we are leveraging 11 independent variables and 1 dependent variable (loan status being approved or not) for our model. 

Approach
The loan prediction issue that we are attempting to tackle falls under the category of predictive analytics. We used a Logistic Regression model at first, as our expected results was in binary format (Yes – Applicant should be granted loan & No – Applicant should not be granted loan). Later, we enforced ensemble modelling and applied multiple machine learning algorithms such as K-Nearest Neighbor, Supply Vector Machine, Naive Bayes, and Gradient Boost.

Results
The dataset we were using, had a high Non-Performing Loan Ratio of 0.4. What we are expecting from our model, was that this ratio will be reduced considerably. The amount of business opportunity lost should also be reduced after implementation. Our best bet was using logistic regression algorithm in our model. As our intended output was in binary format (yes and no), there was no other algorithm we believe to be better. We gained pretty good insights such as maximum customers had applied for a loan amount between $80k to $150k, applicant with 0 dependents had higher chances of approved for a loan, credit history had the highest influence on loan approval etc. 

Business Impact
Our Logistic Regression Model was able to reduce the Non-Performing Loan Ratio from 0.4 to 0.25. Before implementing our model, the total bank loss was $20,580,000, however, after implementing our model the loss went down to $12,862,500. This essentially saved the bank a little more than $7.5 million in direct investments. When we fit out model with Supply Vector Machine, it predicted results with no business opportunity lost. However, after calculating accuracy, logistic regression model ensured far more profitability than SVM model. 
