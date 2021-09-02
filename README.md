# REVENUE AND CUSTOMER AGEING ANALYSIS

This project I do visual data from Equipment Supply Company. The client is supplying equipment to different customers from 3 of his branches. 
The company want to analyze the Revenue and Customer Ageing reports so he can base on them to decide which customer to prioritize when the request is made.

## 1.	Understanding Data Source and Request

Files Data consist of categories: TXNumber ( transaction number) , Equipment, Customer, Area, Monthly Rate, Payment Date, Status, Active, Net Revenue, Deduction

<p></p>


|     No #    |     As a (role)             |     I want (request / demand)                                |     So that I (user value)                                                                                                  |     Acceptance Criteria                                                           |
|-------------|-----------------------------|--------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
|     1       |     Sales Manager           |     To get a dashboard overview of equipment   sales         |     Can follow better which customers and equipment sells   the best                                                        |     A Power BI dashboard which updates data once a day                            |
|     2       |     Sales Representative    |     A detailed overview of      Accounts Receivable Aging    |     Can follow up my customers   status payment to prioritize when customer request or monitor customer credit   quality    |     A Power BI dashboard which   allows me to how   many days customer overdue    |
|             |                             |                                                              |                                                                                                                             |                                                                                   |
## 2. How to Consume Data (Decide Data Storage Decision) 

**Revenue Analysis Report:**
-	 Net Revenue
-	Deduction 
-	Net Profit = Net Revenue – Deduction 
-	Top5 Customer by Net Revenue
-	Revenue by Month
-	Revenue by Payment Status:  
-	Revenue by Equipment
-	Net Revenue by Area Name

**Customer Ageing Analysis:**
-	Customers by Moth: Unpaid/ total 
-	Customer Ageing Details: Focus on Customers who are overdue date

## 3.	Analyze Data to identify Fact/Dimensions/Any Reference Table

After analyze Data, I need to classify fact and Dimension. 
Equipment should be one of the dimension and customer should be one of the dimension and Area that belongs to the supplier location should be another dimension.
Other parts: Monthly Rate, Payment Date, Status, Active, Net Revenue and Deduction should be in fact table. 

## 4.	Power BI Query &Modelling

![datamodel](https://user-images.githubusercontent.com/88467188/131862508-27c5ee76-793d-40df-90c6-d5a195f467e1.png)



## 5.	Power BI Reports

![revenue Analysis](https://user-images.githubusercontent.com/88467188/131862526-20bce753-bc87-497e-af83-cca7783806fc.png)


![Customerageing](https://user-images.githubusercontent.com/88467188/131862491-9e41444e-98ba-4073-9670-5c5b7938fc55.png)

## 6.	Power BI Services.

I published dashboards on Power BI services so anyone can open and interact with Revenue and Customer Ageing Analysis dashboard.
