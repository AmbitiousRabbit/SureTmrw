# SureTmrw

The Sure Tomorrow insurance company wants to solve several tasks with the help of Machine Learning, and you are asked to evaluate that possibility.

* Task 1: Find customers who are similar to a given customer. This will help the company's agents with marketing.
* Task 2: Predict whether a new customer is likely to receive an insurance benefit. Can a trained prediction model do better than an untrained dummy model? Can it do worse? Explain your logic.
* Task 3: Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
* Task 4: Protect clients' personal data without breaking the model from the previous task.

It's necessary to develop a data transformation algorithm that would make it hard to recover personal information if the data fell into the wrong hands. This is called data masking, or data obfuscation. But the data should be protected in such a way that the quality of machine learning models doesn't suffer. 

# Project description of the dataset
  * gender - the gender of the insured individual
  * age - the age of the insured individual 
  * salary - the amount of earned income by the insured individual 
  * family members - the total number of insured members on the insured individual's plan
  * insurance benefits - the total number of benefits received by an insured individual over the last five years

# Project Process

## Step 1 | Access & Study the data
* Open and skim to become familiar with the data
## Step 2 | Prepare the data
* Convert the data to the necessary types
* Find & Eliminate errors in the data
## Step 3 | Analyze the data
* Conduct EDA & SDA while exercising the 5 analytic frameworks (if applicable):
  * What happened? - Descriptive 
  * Why did it happen? - Diagnostic 
  * What will happen? - Predictive
  * How can we make it happen? - Prescriptive
## Step 4 | Build a predictive model 
* Carefully data-masked the customers' information and build a predictive model that can predict whether a customer is more inclined to receive benefits or not
## Step 5 | General Conclusion
* State found insights in a clear, concise manner.
