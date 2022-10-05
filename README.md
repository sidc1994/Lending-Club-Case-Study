# Project Name
> LENDING CLUB CASE STUDY.

# Group Members
> Siddharth Jeetendra Choudhari


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
This project is to evaluate a dataset for a lending club and study their past records with respect to , whether the loan has been cleared of by the lendee or it has been defaulted.
A check is done for different parameters in both categories to see if any pattern emerge which clearly point out towards a defaulted loan.
If this pattern is seen to be repeated in the lending club's next applications for loan, the lending club can rate the application's risk factor and then take precautionary measures on high risk cases to avoid more cases of loan default.

## Technologies Used
numpy
pandas
matplotlib.pyplot
seaborn

## Conclusions
Based on the analysis following are the observations.
1. For the complete dataset, approx 85% people have fully paid their loans and 15% people have defaulted the loans
2. An assumption is considered that this ratio (85:15) will remain constant for analysis of any particular category.
3. So if while analysis if we find this ratio more towards the defaulted side then we can term that particular scenario as risky.
4. Following parameters were analysed and their conclusion are highlighted below
    
    a. term
    Conclusion - High term incresed the risk of default

    b. public records of bankruptcies
    Conclusion - Risk increases even if there is a single public record of bankruptcy.

    c. purpose
    Conclusion - 7 common purposes are identified which have high probability of defaulting the loan. The category of "small business" carries the maximum risk and highest probability of defaulting the loan

    d. state
    Conclusion - 16 states are identified, applications from which have a high probability of defaulting the loan. 

    e. revol_utilisation
    Conclusion - If the revol_utilisation of any individual is above 50%, it is more likely that the individual will default the loan.

    f. Percentage of installment w.r.t monthly income
    Conclusion - If any individual is carrying an installment which is more than 10% of his/her monthly income then the risk of defaulting the loan increases. 


## Acknowledgements
Give credit here.
- This project was inspired by UPGRAD's case study for the EPPG/MS program in AI and ML


## Contact
Created by [@sidc1994] - feel free to contact me!

