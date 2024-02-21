# Solve Real-World Data Problems with SQL
The queries showcased here were employed to advance skills through a LinkedIn Learning course, led by Jess Ramos. Access the course: Master Real-World Data Challenges with SQL.
Key SQL concepts covered in this course include:

*Utilizing Common Table Expressions (CTEs) for Product Analytics
*Employing CASE statements for Data Transformation
*Merging Multiple Data Sources with UNION
*Manipulating Hierarchical Data using Self Joins
*Leveraging Window Functions for advanced analytics

## Challenge 1: Pull descriptive statistics with a CTE
### Calculating descriptive statistics for monthly revenue by product
Task: For the year 2022, provide a report that answers the following questions:
1. How much revenue does each product usually generate each month?
2. Which product had the most success throughout all of last year
3. Did either product fluctuate greatly each month or was the month-to-month trend fairly consistent?

## Challenge 2: Explore variable distributions with CTEs
### Exploring variable distributions with CTEs
Task: Find the distribution of users across the number of times the email link was clicked per user

## Challenge 3: Payment funnel analysis with CTEs
### Payment funnel analysis with multiple CTEs
Task: Provide a funnel analysis to identify the farthest point in the payment process where users get to and where users leave (or face errors).

## Challenge 4: Create binary columns with CASE
### Flagging upsell opportunities for the sales team
Task: Provide a report that identifies potential customers that present as a potential upsell opportunity by meeting the following conditions:
* Have at least 5,000 registered users
* Have only one product subscription

## Challenge 5: Pivoting rows into aggregated columns with CASE
### Tracking user activity with front end events
Task: Provide a report that tracks user activity to identify whether new design changes positively or negatively impact the customer support page

## Challenge 6: Combine product tables using UNION
### Combining 2 Product Tables into 1
Task: From the two product tables, find the number of active subscriptions that will expire each year.

## Challenge 7: Unpivoting columns into rows using UNION
### Analyzing Subscription Cancelation Reasons
Task: Find the percentage of canceled subscriptions that reported "Expensive" as one of their cancelation reasons.

## Challenge 8: Employee-manager data with a self join
### Pulling employee/manager data with a self join
Task: Provide an email list for the Sales department such that each employee's manager will get an email. If the employee does not have a manager, their email can be included in the email list directly.

## Challenge 9: Comparing rows within the same table
### Comparing Month-over-Month (MoM) Revenue
Task: Provide a report that highlights months where the revenue was up from the previous month.

## Challenge 10: Get running totals with window functions
### Tracking Sales Quota Progress Over Time
Task: Find the running total of sales revenue, running total, and percent quota for each sales employee on each date that they make a sale.

## Challenge 11: Timestamp differences with LEAD()
### Tracking User Payment Funnel Times with LEAD ()
Task: For user 38844, pull their payment funnel data to investigate the time it takes to complete the steps in their payment process.

## The Data
<span class="image main"><img src="https://www.codingame.com/work/servlet/fileservlet?id=57963837776032" alt="" /></span>

<span class="image main"><img src="https://www.codingame.com/work/servlet/fileservlet?id=57965554724304" alt="" /></span>

## Subscription Payment Funnel Stages
<span class="image main"><img src="https://www.codingame.com/work/servlet/fileservlet?id=57963977632205" alt="" /></span>
