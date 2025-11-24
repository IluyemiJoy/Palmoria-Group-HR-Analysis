# Palmoria-Group-HR-Analysis
The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues  bordering on gender inequality in its 3 regions.
The project is focused on uncovering the presence of employee discrimination and inequality

---

<h2>1.	Project Overview</h2>

 <h3>•	Problem Statement</h3>
 The recent negative media portrayal of The Palmoria Group as "the Manufacturing Patriarchy" has created a severe reputational crisis that directly endangers the company's strategic growth ambitions. This publicity exposes the organization to significant operational, legal, and brand risks by highlighting perceived systemic gender inequality. The immediate business problem is to objectively diagnose, quantify, and eradicate gender-based disparities across all people processes to safeguard the company's reputation, ensure long-term viability, and build an equitable workplace that facilitates scalable growth.
  
  <h3>•	Objectives:</h3>
  
  The major objectives of the project is to:


• Diagnose Gender Representation Equity

• Establish Pay Equity and Identify Gaps

• Ensure Performance Management Fairness

---

<h2>2.	Data Source</h2>

The data was obtained online from Kaggle

---

<h2>3.	Methodology</h2>

<h3>•	Tools Used</h3>
The dashboard was built using the following tools and technologies

-	**Microsoft Excel** – Main data analysis and visualization platform used for report creation
-	**Power Query** – Data transformation and cleaning layer for reshaping and preparing data
-	**Pivot Table** – Used for analysis
-	**File format** - .xlsx for development and .png for dashboards preview

<h3>•	Key Data Cleaning Processes</h3>

i.	Assigned a generic gender status to these employees 

ii.	Took out employees that are without a salary

iii.	Lastly, some departments are indicated as “NULL”. These departments were taken out.
  
<h3>•	Key Functions UsedD </h3>

**-	Churn rate** = DIVIDE([Churned], [Total Customers], 0)

**-	Avg Credit Churned** = CALCULATE(AVERAGE('Customer_Churn_Records'[CreditScore]),'Customer_Churn_Records'[Churn status] = "Churned"
-	Compilation of all DAX Measures

---

<h2>4.	Key Insights and Findings</h2>

This multifaceted dashboard provides a 360-degree view of the churn problem:

<h3>•	Demographic Analysis</h3>

<img width="1599" height="862" alt="Image" src="https://github.com/user-attachments/assets/3a3fac20-ea8a-4156-858d-65c468e399b6" />

[Dashboard Preview](https://github.com/IluyemiJoy/Bank-Churn-Analysis-using-PowerBI/blob/main/Demographic%20Analysis%20Dashboard%20Demo.PNG)

This tab analyzes the “who” – the geographic and demographic composition of customers
  -	Customers from Germany exhibit a significantly higher churn rate compared to other countries.
  -	Males across all age groups were identified as having a disproportionately higher churn rate
  -	Churning is significantly low across balances and almost equally distributed across all card types


<h3>•	Behavior & Engagement Analysis</h3>

<img width="1599" height="862" alt="Image" src="https://github.com/IluyemiJoy/Bank-Churn-Analysis-using-PowerBI/blob/main/Behaviour%20and%20Engagement%20Analysis%20Dashboard%20Demo.PNG" />

[Dashboard Preview](https://github.com/IluyemiJoy/Bank-Churn-Analysis-using-PowerBI/blob/main/Behaviour%20and%20Engagement%20Analysis%20Dashboard%20Demo.PNG)

This tab explores the reasons for churning among customers
  -	Customers with a Basic product holding have marked a significantly higher churn rate
  -	Overall, a larger percentage of the customers have laid a complaint which in turn leads to an alarming churn in customers that have made complains 


<h3>•	Churn Risk Analysis</h3>

<img width="1599" height="862" alt="Image" src="https://github.com/IluyemiJoy/Bank-Churn-Analysis-using-PowerBI/blob/main/Churn%20Analysis%20Dashboard%20Demo.PNG)" />

[Dashboard Preview](https://github.com/IluyemiJoy/Bank-Churn-Analysis-using-PowerBI/blob/main/Churn%20Analysis%20Dashboard%20Demo.PNG)

This tab profiles the customer churn risk
  -	The longer the customer stays the higher the tendency to churn
  -	Product holding and point earned have very weak hold on the churn rate

