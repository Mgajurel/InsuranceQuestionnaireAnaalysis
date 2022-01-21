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

1. Choosing 'Software Development' as the business that needs Employee Compensation, went through all the questions asked by the carrier to receive a suitable quote for my assumed business.
   | Employee Compensation  Questions |
   | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | |
   | |
   | Carrier A | Carrier B |
   | 1\. Zip Code?<br>2\. What's your industry?<br>3\. Do you have any employees?<br>4\. How many employees do you have? (Include both part-time and full-time employees in your response. Exclude business owners and officers.)<br>5\. Where does your business operate? (If you lease space on an ongoing basis but also work from home or a job site, select "I lease space from others." If you work from home but also have a temporary space lease or work from a job site, select "I run my business out of my home.")<br>6\. Where is your business located?<br>7\. When did you start your business? (Drop Down - Brand New, Started last year, Started 2 years......., started 10 or more years)<br>8\. How is your business structured? (Drop Down - Corporation, Partnership, Individual/Sole Proprietor, Sub-Chapter Corp)<br>9\. Do you want to include coverage for any owners/officers? (Drop Down - No, Yes buy coverage for 1 owner/officer........., Yes buy coverage for 5 or more owners/officers)<br>10\. Do any staff install computer hardware at client locations? (Yes/No)<br>11\. Do any employees travel frequently for sales, consultation, or programming? (Yes/No)<br>12\. Do you provide any staffing services? (Yes/No)<br>13\. In the past 3 years how many Workers' Compensation claims were reported? (Drop Down - None, 1 .... 6 or more)<br>14\. Do you use any volunteers or donated labor? (Yes/No)<br>15\. Do you have multiple locations in more than one state? (Yes/No)<br>16\. Insured first name<br>17\. Insured last name<br>18\. Doing business as (optional)<br>19\. Business website (optional)<br>20\. Business address line 1<br>21\. Business address line 2<br>22\. City (Drop Down based in Zip Code)<br>23\. Contact email<br>24\. Contact phone | 1\. What is the zip code of your primary business location?<br>2\. What kind of work do you do?<br>3\. What is the name of your business? (conditioned: if DBA then take DBA also.)<br>6\. Phone number<br>7\. Email (Conditioned with Primary contact is the business owner, if ticked then following needs to be provided)<br>8\. Owner's first name<br>9\. Owner's last name<br>10\. What date did your business begin under current ownership? (Datetime/Calender)<br>11\. How is your business registered? (Tick  Corporation, Individual, Joint Venture, LLC, Partnership, Limited Partnership, S Corporation)<br>12\. Is the Corporation non-profit? (Yes/No)<br>13\. Number of executive officers (Number)<br>14\. Number of employees (Not including owners and officers)<br>15\. Address line 1<br>16\. Address line 2<br>17\. Zip<br>18\. City, State (Conditioned picker for This is the mailing address)<br>19\. Total annual employee payroll including owners (number in dollars)<br>20\. Do you have a website? (Pick Yes/No) (Asked Site Url if picked Yes)<br>21\. Has your company had any claims in the past 5 years? (Pick Yes/No)<br>22\. Is workers' compensation coverage currently in effect? (Pick Yes/No)<br>23\. Has your workers' compensation coverage been declined, canceled, or non-renewed within the last 3 years? (Pick Yes/No)<br>24\. Do you hire other labor beside your employee?(Pick Yes/No)<br>25\. How many branches do you have? (Number) |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |
   | |

2. After collecting questions from the two carriers, manually went through the questions to find those questions with difference in phrasings, but similarity in implication of info being assessed.
   (This information)
