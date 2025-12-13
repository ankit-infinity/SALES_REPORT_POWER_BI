# SALES_REPORT_POWER_BI

# OVERVIEW;

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/overview.png)

This project entails developing a comprehensive sales analysis system for 'ELECTROHUB',a multiregion retail company .
The core purpose is to leverage existing sales data to generate actionable insights,enabling management to monitor performance across all stores and regions effectively
.The project will focuse on identifying key performance indicators(KPIs)such as top and bottom selling products,region sales,sales trend,revenue drivers. 
The project outcome will be a suite of dynamic,visuals reports design to support data driven decision making ,optimize inventory management and enhance 
overall buisness stratergy.

# DATASETS:

This dataset consists of four table one fact table and three dimension table

1.FACT TABLE CONSISTS OF THE FOLLOWING FEATURES:
 
 CUSTOMER_ID
 
 DATE
 
 PROMOTION ID
 
 PRODUCT ID
 
 UNIT SOLD
 
 TOTAL SALES
 
 DISCOUNT
 
 DISCOUNT PERCENTAGE
 
 NET SALES
 
2.DIM CUSTOMER TABLE 

 CUSTOMER ID
 
 CUSTOMER NAME 
 
 CITY
 
 STATE
 
 PINCODE
 
 EMAIL ID
 
 PHONE NUMBER
 
 3.DIM PRODUCT TABLE
 
 PRODUCT ID
 
 PRODUCT NAME
 
 PRODUCT LINE
 
 PRICE(INR)
 
 4.DIM PROMOTION TABLE
 
 PROMOTION ID 
 
 PROMOTION NAME 
 
 AD TYPE
 
 COUPON CODE
 
 PRICE REDUCTION TYPE
 
# BUISNESS REQUIREMENTS:

1.Top/Bottom 5 product by sales/profit/quantity sold  

2.How do sales vary over time(daily,monthly,quaterly,annually)

3.Compare sales/profit/quantity sold between any two period.

4.average discount offer to each discount category.

5.show relationship between sales and profit.

6.total no of orders

7.ShoW sales by different cities

8.show sales/profit/discount/net sales/all remaining fields for each order
that could be filtered using visuals filter(prOduct/date/customer id/promotion category)

# METHODOLOGY USED:

1.DATA PROFILING AND TRANSFORMATION

2.MERGE QUIERES (LEFT OUTER JOIN)

3.DATA MODELLING

4.CARDINALITY

5.DATA VISUALIZATION USING CHARTS

# INSIGHTS:

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/top_bottom%205%20analysis.png)

TOP 5 PRODUCT BY:
 
SALES:

1.APPLE IPHONE 14
2.APPLE MACBOOK AIR
3.SONI BRAVIA SS*TV
4.SAMSUNG GALAXY S21
5.HP PAVILLION LAPTOP

QUANTITY:

1.APPLE IPHONE 14
2.RAYMOND SUIT
3.FOSSIL SMARTWATCH
4.ZARA CASUAL SHIRT
5.IFB MICROWAVE OVEN

PROFIT:

1.APPLE IPHONE 14
2.APPLE MACBOOK AIR
3.SONI BRAVIA SS*TV
4.SAMSUNG GALAXY S21
5.HP PAVILLION LAPTOP

BOTTOM 5 PRODUCT:

SALES:

1.TOPPERWARE LUNCH BOX
2.LOREAL SHAMPOO
3.NIVEA BODY LOTION
4.DOVE SOAP PACK
5.COLGATE TOOTHPASTE

QUANTITY;

1.NIVEA BODY LOTION
2.TOPPERWARE LUNCH BOX
3.MILTON THERMAL FLASK
4.FABINDIA KURTA
5.BOROSSIL GLASS SET

PROFIT:

1.TOPPERWARE LUNCH BOX
2.LOREAL SHAMPOO
3.NIVEA BODY LOTION
4.DOVE SOAP PACK
5.COLGATE TOOTHPASTE

Compare sales/profit/quantity sold between any two period.

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/sales%20over%20two%20period.png)

by applying filter context

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/filter.png)



















