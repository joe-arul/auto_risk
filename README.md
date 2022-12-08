# auto_insure

[20-50 million](https://www.iii.org/fact-statistic/facts-statistics-auto-insurance) people are injured in auto accidents globally with an accrued cost of [$518 billion](https://www.asirt.org/safe-travel/road-safety-facts/). Since the first insurance claim in 1897, car insurance companies have worked to cover the expenses incurred from these incidents -  from property damage, medical expenses, lost wages, to legal fees.
With these enormous expenses insurance companies are obligated to take any opportunity to optimize their solvency and minimize losses. A large part of this is appropriately pricing policies and coverage, meaning, to not undercharge for drivers that cause catastrophic, costly incidents and not overcharge for safe customers that might never make a claim and could easily switch providers.

The previous underwriting and risk evaluation process for insurance companies could take a month with all the manual steps involved with generating a car insurance claim. But with so many incidents and claims, insurance companies are already applying technologies such as machine learning to improve their processes. Today you can receive car insurance in an hour and the company has already assessed your risk while considering things like driving history, credit history, and prevalence of fraud or inclement weather in your location. Part of that automated risk assessment includes the consideration of the driver's car model and attributes.

The focus of this project will be to develop a binary classification model to better predict whether risk is associated with a car based on its attributes. This will aid in the risk assessment process to offer more individualized rates car insurance rates, promoting customer retention and company solvency.


**Automobile Data Set ([UCI source](https://archive.ics.uci.edu/ml/datasets/Automobile)):**
This data from the UCI Machine Learning Repository was donated from Carnegie Mellon University and consists of 3 sources (1985 Ward's Automotive Yearbook, Insurance Services Personal Auto Manuals, and IIHS Insurance Collision Report). A paper was written in 1988 by UCI ([Source](https://escholarship.org/content/qt68f860zb/qt68f860zb.pdf?t=q67ipi)) which used this data in their development of 'instance-based prediction' but did not reference the context of car insurance whatsoever. Similarly a Kaggle competition was held in 2020 with this data where users experimented with a range of predictive models but with a sole focus on model performance rather than deployment. 

This establishes a need for our model, as the data has been used to train models but the results from the Kaggle competition are kept private along with the training test split to compare performances. 
The data has 205 records and 26 features (15 continuous, 1 integer, and 10 nominal), including the integer outcome ranging from -3 to +3.  
