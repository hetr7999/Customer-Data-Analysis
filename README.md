                                                                    Customer Data Analysis

Use Case1 - I presumed that the Data provided in excel sheets is the customer base of the XYZ company. In that case, I have made some assumptions which will be highlighted.

Use Case2- The Data provided simply provides insights about every person and performs some analysis based on their age and occupation.

In any analysis ETL (Extract Transform Load) plays an important role so that we get clean data to work with in our analysis.
Extract Data – 
A.	Data was present in the excel sheet provided.
Clean Data-
A.	Check for Duplicate Values – There were duplicate values present in the data.
B.	Check for Missing Values – No missing values were present.
Transform Data-  
A.	Add Missing Columns – Created New columns to perform Analysis.
Load Data-  
A.	Connect Data to Tableau to perform Analysis.


Observations from Data –
1.Duplicate Values (First Name & Last Name) –
There are many persons with same name so there are two ways to handle it.
a.	Remove the record in order to perform analysis.
b.	Classify the record based on salary and occupation if both of these are same then no of children can be a factor for consideration.

2. Useless Values 
 a.Considering UseCase1 – If there are No Children then for that person IDZ application will be of No use. So, we can consider it as a garbage values and ignore that values in   our analysis.
 b.Considering UseCase2 – This Data can be used to predict different things like fertility rate etc.
3.New Columns (Full Name) 
 a.Created New Column Full Name – Merged (First Name & Last Name) in order to display Name of the customer as a whole because first name and last name.
4. New Columns (Income Class)  
 a. If Salary > 7000 =Upper else Middle.
 
All the other observation are visualized in Dashboard.

Discount Dashboard 
1. Discount Analysis
 In this scenario I took top 15 people who have lowest salary and no of children greater than two so we can offer such customers a discount considering their financial status.
Now there is different scenario is the salary given by customer is fake. So, we can take their income proof before providing discount.
2. Single Women with Income Less than 2000 and No of children > 2 
In this case I performed collaborative filtering to get these records so we can support single women who have separated and have less income.
All the above observation were complicated to understand, So I tried to explain it. All other Observations are self explanatory in the dashboard.

Dashboard Link - https://public.tableau.com/profile/het.raval#!/vizhome/Data-Analysis-IDZ/DiscountDashboard

Note - Please View it in Full Screen Mode and Use Tabs to view other Dashboards


Screenshots -


1. Discount Dashboard -

![Screenshot (346)](https://user-images.githubusercontent.com/57358161/115661351-f2c03900-a35a-11eb-9b73-78592a92f206.png)

2. Gender and Occupation Classification Dashboard

![Screenshot (347)](https://user-images.githubusercontent.com/57358161/115661455-15eae880-a35b-11eb-8139-cb68bedd1a46.png)


3. Customers Data Dashboard -

![Screenshot (348)](https://user-images.githubusercontent.com/57358161/115661476-1d11f680-a35b-11eb-9fb1-d58a1903e66b.png)


4. Median Salary Dashboard -

![Screenshot (349)](https://user-images.githubusercontent.com/57358161/115661503-269b5e80-a35b-11eb-8035-7cbe1d159376.png)


