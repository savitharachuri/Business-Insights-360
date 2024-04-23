# Business-Insights-360
Power BI Dashboard visualizing Business Insights pertaining to various users or stakeholders

# Dataset Overview
AtliQ Technologies is an emerging Business Consulting and IT organisation in India, which is known for their e-commerce and retail businesses in selling various types of computer devices and accessories. The dataset considered is real-time data from AtliQ Technologies. 

# Process Overview
In order to understand the performance of the business, developing dashboard views depending on the interests of the stakeholders is necessary. In this case, the following views are considered:

## Finance View 
Finance view dashboards are referred by stakeholders of every level to understand the profit or loss for the revenue generated with respect to different periods and regions etc.

## Sales View
Sales view dashboards are referred by stakeholders of every level to understand customer behaviour and what are the top or least products sold.

## Marketing View 
Marketing view dashboards are referred by stakeholders at executive level to understand where is the need to invest in advertising or promoting a particular product to customers.

## Supply Chain View 
Supply Chain view dashboards are referred by logistic stakeholders to understand the operations such as delivering the products to customers and allow businesses to identify opportunies of improvement.

# Power BI Dashboards Overview
The section gives technical details used to develop the dashboards in Microsoft Power BI attached in the above folder.
 
 -> **Transforming data** in Power Query using **M-language**, to tackle data cleaning tasks such as handling NULL values and duplicates, capturing most recent date with List.max 
    function. Organising the tables into different folders according to dimension tables and fact tables, hiding the tables that are unecessary.

 -> Identifying Key Performing Information (KPIs) for various views and calculating them using either by creating custom columns or measures using **DAX language**. Making use of 
    appropriate graphs to represent the data.
