# Predictive Modeling and Insights for Residential Mortgage Approval

## **Project Overview :**

The Mortgage Pre-Fund Review team reviews residential mortgage files, submitted from branches across a country to identify errors in application policy, including non-compliance or deficiencies in supporting documentation. 
Ideally, each submission would be correct on the first attempt, but often applications must be returned to the branch for corrections before Pre-Fund can approve them. This repeated review process places additional strain on the Pre-Fund team and can cause significant delays in mortgage approval, ultimately impacting the customer experience. The goal is to streamline submissions, reduce errors, and improve efficiency in the mortgage approval process.

<ins>Definitions from the dataset</ins> -

• _First Time Right_ : When the application is correctly approved at the first time.

• _Time to Pre-Fund Decision_: # of business days between ‘Details’[Application Date] and ‘Cases’[Resolved Time]

• _Case Time_: # of business days between ‘Cases’[Create Time] and ‘Cases’[Resolved Time]

• _Notification Time_: # of business days between ‘Notifications’[Create Time] and ‘Notifications’[Resolved Time]

• _Not First Time Right Branch Time:_ (Case Time) – (SUM of all Notification Time for the associated Case)

• _Business Days_: Monday to Friday, not including Ontario Public Holidays

To measure the impact of applications not being first time right.

<ins>We analyse on the bases of the following</ins>:

• The Regions and Districts were the worst performing when it comes to first time right.

• The impact on ‘Time to Pre-Fund Decision’ and ‘Case Time’ when a case is not first time right.

• The average number of notifications associated with each case and are there any trends positive or negative.

• If a case is not first time right, what is the percent of total case time spent with the branch making revisions vs. Pre-Fund working the notifications.

## Predictive Modeling:

To build a predictive model using Jupyter and Scikit-learn to predict FTR – First Time Right. Additionally explain how to use the model to drive improved Operations or Business Process.

The project contains the graphs of the trends as mentioned above in addition to a powerpoint presentation for the analysis.
