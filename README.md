# SALES_REPORT_POWER_BI


# REPORT LINK : 

https://app.powerbi.com/links/LLMu3288DO?ctid=aa83b4a7-28d2-45a8-b2ce-208211922a81&pbi_source=linkShare


# OVERVIEW;

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/overview.png)

This project entails developing a comprehensive sales analysis system for 'ELECTROHUB',a multiregion retail company .
The core purpose is to leverage existing sales data to generate actionable insights,enabling management to monitor performance across all stores and regions effectively
.The project will focuse on identifying key performance indicators(KPIs)such as top and bottom selling products,region sales,sales trend,revenue drivers. 
The project outcome will be a suite of dynamic,visuals reports design to support data driven decision making ,optimize inventory management and enhance 
overall business stratergy.

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

6.DAX FUNCTIONS LIKE:CALENDARAUTOFUNCTION TO CREATE DATE TABLE 

SUM OF NET SALES= CALCULATE(SUM('FACT TABLE'[NET SALES]),ALL('date table 1'),USERREALTIONSHIPS('date table 2'[date],'fact table'[date(dd/mm/yyyy)])).

Total profit = CALCULATE(SUM('FACT TABLE'[profit]),ALL('date table 1'),USERREALTIONSHIPS('date table 2'[date],'fact table'[date (dd/mm/yyyy)])).

quantity sold = CALCULATE(SUM('fact table'[Units Sold]),ALL('date table 1'),USERELATIONSHIP('date table 2'[Date],'fact table'[Date (dd/mm/yyyy)]))


# INSIGHTS:

1.ORDERS: Total of 3510 orders, indicating steady demand.

2.GEOGRAPHY: Sales are concentrated in major Indian cities like Delhi,Mumbai,Bengaluru,chennai and kolkata

3.PROMOTIONS: Weekend flash sales drives the highestdiscounts and engagement.

clearance sale is the second most impactful.

festive diwali shows minimal discount impact.

4.profit vs sales: strong positive correlation higher profit directly indicate higher net sales.

5.Trend over time: sales show consistent growth with spikes peaking around 2023,indicating impured performance overtime.
        

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/top_bottom%205%20analysis.png)

1.Apple i phone 14 is the top performer leading in sales ,quantity and profit.apple product dominate the ttop position indicating
  strong brand demand.
  
2.Electronics contribute the highest revenue and profit overall,

3.low priced FMCG items (tupperware lunch box, loreal shampoo, colgate toothpaste)appear in the bootom of the sales and profit.despite moderate quantities

4. high quality doest not always mean high profit as seen in some bottom profit products.

conclusion: promote high profit products and re evaluate low margin items.


Compare sales/profit/quantity sold between any two period.

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/sales%20over%20two%20period.png)

by applying filter context

![alt text](https://github.com/ankit-infinity/SALES_REPORT_POWER_BI/blob/main/images/filter.png)

# RECOMMENDATION:

1.Focus on high performing cities:

strengthen inventory and marketing efforts in top selling cities to maximize returns from existing demand.

2.optimize promotions:

Continue and expand WEEKEND FLASH SALES AND CLEAREANCE SALES,as they generate the highest impact.rework
or redesign low performing promotion like FESTIVE DIWALI.

3.profit driven stratergy;

since higher profit aligns with higher net sales,prioritize profitable categories and avoid excessive discounting

4.sales planning;

use historical sales spikes to plan stock in advance , especially during peak periods.

5.store level optimization:

compare store performance regularly and apply best practices from high performing stores across the electro hub network.

6.focus on high performing products like apple ,mackbook and premium electronics ensuring adequate stock across all stores

7.replicate sale stratergies of top performing stores /products in other location to maximise revenue

8. review low performing products and consider discounts ,bundles,or replacement with better demand items.

9.reduce shelf space for consistently under performing items.

10.use store level insights to optimise inventory palnning and avoid overstock low margin products














