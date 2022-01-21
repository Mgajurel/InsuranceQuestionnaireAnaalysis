# InsuranceQuestionnaireAnalysis

Among the various available insurance type I have selected **Employee Compensation** in order to carry this analysis. Employee compensation refers to the benefits (cash, vacation, etc.) that an employee receives in exchange for the service they provide to their employer.

I have selected two real carriers and went through their questions to get a quote. For the ease of discussion we call then **Carrier A** and **Carrier B**

## Assumptions

Following assumptions has been made when collecting questions for carrier and analyzing them.

1. 'Software Development' is the business that needs Employee Compensation product.

2. The data types for the questions are same or at least can be converted to similar representation.
   eg: Business Start date takes Datetime in one case and Drop down menu with values started last year, started 2 years ago, started 3 years ago, started 4 years ago, started 5 or more years ago. In both case we can get a count for total number of years.

3. Any question should fall into a category, eg: Business Information, Contact Information, Operations etc.

## Methodology

1. Choosing 'Software Development' as the business that needs Employee Compensation, went through all the questions asked by the carrier to receive a suitable quote for my assumed business. (see sheet 'Collected Questions' in assignment.xlsx)

2. After collecting questions from the two carriers, manually went through the questions to find those questions with difference in phrasings, but similarity in implication of info being assessed. (see sheet 'Question Analysis')

3. Categorized the questions into the given categories (see sheet 'Question Analysis')
   -Company Information
   -Business Details
   -Location
   -Contact Information
   -Operations

4. Collected the choice type for the similar questions.
5. Created Embeded json to represent the similar questions.

## Findings

1. For a few sample questions and a number of carriers, manual intervention seems effective
   since it results in the least number of false positives.
2. In case of huge number of questions and similar number of carrier, a manual approach does
   not seem feasible. A probable solution would be rueducing the manual work by using Machine Learning for string comparison.

## Embeded JSON
