# Examine-the-audit-of-controls-over-credit-card-transactions

# Problem: 
•	This case is based upon a case from the Ernst and Young Academic Research Center, also known as EYARC. The case is called Payment(P)-card. The use of the case material complies with the copyright therein. Specifically, the EYARC copyright prohibits posting case solutions on any publicly accessible platform. Thus, before using these materials, data is modified that meets all requirements and their respective materials. The case uses real data from Oklahoma State University. Data set that we'll use for this case is from the State of Oklahoma Payment Card Purchases. 
•	Payment cards or P-cards are business credit cards that some employees are permitted to use to purchase necessary goods and services for work. Employees can use the P-card to make appropriate business purchases and then later seeking for reimbursement. 
•	The Oklahoma state government does not want its employees to use P- cards for just anything. The organization then authorizes the use of P-cards has rules or controls about what a user of a P-card is allowed to spend money on, and how much they're allowed to spend. 

# Task: 
•	Our job in this case, is to act as an auditor engaged to audit the P-card transactions to ensure that those using the P-cards are following the stated controls. Specifically, you’re asked to perform an audit of the purchasing cards, the P-cards that are used on campus. Your job then as the auditor is to go into the data to examine whether or not these controls have been violated. 

# Solution: 

Let's think about how we can implement these controls. In general, there are two ways to implement controls, in a preventative manner or in a detective or oversight manner. In a preventative setting, the controls are set up such that they do not allow an employee to do a certain thing. Now a second way to implement these controls is as detective or monitoring controls such that the employee is not prevented from doing something, but rather a log or a record is kept, and after the fact, the record can be examined and reviewed to see whether or not an employee has made a purchase for over $5,000(for example). 
Finally, let's think about how employees might circumvent, subvert, or get around these controls. For example, an employee might try to get around the control that limits individual purchases to less than $5,000 by splitting a larger transaction into multiple smaller transactions. While we don't examine this possibility in this case, it's important for the auditor to keep an open mind and to think skeptically about how an employee might circumvent the system.

Now we'll load, view, transform, and clean the data to make sure it's ready for use. This process is often called ETL for extracting, transforming, and loading data, data merging, data prep, among many other names. 
Once the data is loaded and cleaned, we'll explore it a bit. This process is often called EDA or exploratory data analysis. In this case, we'll have three specific controls that we're testing. 
1.	Individual transaction < $5000
2.	Total purchases for the month <10000
3.	Total purchases for the year < 50000
Finally, we'll check all the data to examine whether any of the three controls have been violated. We'll then make a list of violations and follow up with management to see if they have explanations for these violations. 

![image](https://user-images.githubusercontent.com/50633864/147260176-43ea97c4-c0c4-4713-95c9-829de7f10850.png)
