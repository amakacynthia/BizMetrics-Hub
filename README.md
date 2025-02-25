# BIZMETRICS-HUB ANALYSIS

![SALES](https://github.com/user-attachments/assets/14d1b20d-3083-44b1-aa38-da0495546497)


## TABLE OF CONTENT
- [BIZMETRICS-HUB OVERVIEW](#bizmetrics-hub-overview)
- [DATA DICTIONARY](#data-dictionary).
- [DATA SOURCE](#data-source).
- [TOOLS](#tools)
- [KEY PERFORMANCE INDICATORS](#key-performance-indicators).
- [DATA CLEANING](#data-cleaning).
- [DATA ANALYSIS](#data-analysis).
- [DESCRIPTIVE ANALYSIS 1](#descriptive-analysis-1)
- [DESCRIPTIVE ANALYSIS 2](#descriptive-analysis-2)
- [GENERAL DASHBOARD](#general-dashboard)
- [INSIGHTS](#insights)
- [CONCLUSIONS](#conclusions)
- [RECOMMENDATIONS](#recommendations)
- [APPRECIATION](#appreciation)
  
## BIZMETRICS-HUB OVERVIEW
This dataset is a comprehensive collection of sales transactions that captures key details across multiple dimensions of business performance. Overall, the data serves as a robust foundation for analyzing sales trends, evaluating product performance, and understanding customer behaviors, making it an invaluable resource for strategic decision-making and targeted marketing initiatives.

## DATA DICTIONARY

* Order ID : This column contains a unique identifier for each order transaction. It helps track individual purchases.
* Order Date: This column contains the date when the order was placed. Useful for analyzing sales trends over time.
* Customer ID:This column xontains a  unique identifier for each customer, allowing for customer behavior analysis.
* Gender: This column contains The gender of the customer (Male/Female).
* Region: The geographical location where the order was placed.
* Product Category: This column contains the broad category of the product (e.g., Electronics, Fashion, Home Appliances).
* Product Name: This column contains the specific product purchased.
* Quantity Ordered: This column contains the total number of units purchased in an order. Important for stock and demand forecasting.
* Unit Price: This column contains the unit price per unit of product.
* Payment Method: This column contains the mode of payment used (e.g., Credit Card, PayPal, Bank Transfer).
* Total Revenue: This column contains the total earnings from the order.

## DATA SOURCE 
This dataset is from Delmich Consult
- [Download here](blob:https://web.whatsapp.com/1152bb40-e1a1-4a5f-9d25-c47ec5f478d1)

## TOOLS
- Excel
- Powerbi
 
## KEY PERFORMANCE INDICATORS
- Total Revenue
- Total Customers
- Average Order Value
- Total orders

## DATA CLEANING
The data was initially imported from an Excel file, where the first row contained the column headers. Key cleaning steps included:

* Header Adjustment:
The first row was set as the header, and subsequent rows were re-indexed for clarity.

* Data Type Conversion:
Date fields were converted to proper datetime formats, while numerical columns such as Quantity Ordered and Unit Price were formatted as numbers to ensure accurate calculations.

* Handling Inconsistencies:
Text fields like Gender and Payment Method were standardized to maintain consistency across the dataset.

* Duplicate Removal:
Duplicate records were identified and removed to ensure data integrity.

**These steps ensured that the dataset was reliable and ready for accurate analysis and visualization.**

## DATA ANALYSIS

![Quotefancy-2786790-3840x2160](https://github.com/user-attachments/assets/b4cba3d9-f1fc-4194-bd7f-d437f73d5be8)

## DESCRIPTIVE ANALYSIS 1

Descriptive analysis summarizes historical data to reveal key trends and patterns, helping you understand **what has happened**. It covers metrics like totals, averages, and distributions to provide a clear overview of past performance.

* Total Revenue = $506
* Total Customers = 274
* Average Order Value =$272.86
* Total Order = 1856
  
* Total Regions covered = 3
  - Europe
  - Asia
  - North America
    
 * Payment Methods Used = 4
   - Paypal
   - Appe Py
   - Credit card
   - Crypto
## DESCRIPTIVE ANALYSIS 2

*  Monthly Sales Trend:
   
 ![MONTHLY SALES TREND](https://github.com/user-attachments/assets/ec885a34-23a3-4bb9-99de-a94af0f472bf)

   From the analysis done, it is seen that in **may the highest revenue ($56,716)** was generated, while in December($56,241) was realized, followed by August ($53,363),and in March  ($45,545), in July ($43,940) was acquired, then  in June ($42,033) was garnered from the business. Going forward by September it made a total of ($37,642), but  Ocotober yeilded ($37,415), also for  Feburary($36,936) was secured ,meanwhile in  November($35,892) was gained , in January  ($32,285)was collected  and in **Apirl ($28,420)** was poorly made from the business.
   
* Revenue by Product Category:

![rebyproduct](https://github.com/user-attachments/assets/6ff7605f-9a0f-43a5-9bbb-1e0f20166619).
  
  Products sold in this business was categorized into three ; Electronics, Home and living and Apparel. The **Electronics category realized the highest revenue of ($177k)** while the Home and living realized ($170k) and the Apperal made ($159k).
  
* Revenue by Region:
  
![region](https://github.com/user-attachments/assets/c61f2c5b-ee17-48f0-89e7-5c16bc788a68)

  From the three regions covered by the business, Europe realized the most revenue followed Asia and lastly North America realizing ($188k),($164k) and ($155k) respectively.

  * Gender-Wise Purchase Behavior:
    
![gender](https://github.com/user-attachments/assets/bc5fef39-822a-4f87-96c7-cdc290e27155)
    
The analysis of customer purchasing patterns by gender reveals that female customers make more purchases than male customers,with the female customers dominating with over **53.54%** than their male counterparts.

 * Payment Method Distribution:
   
![payment ](https://github.com/user-attachments/assets/89e64116-e364-4f1e-bb71-3c7e56ac4af8)
   
   The analysis of payment methods shows that PayPal is the most preferred option, followed by Apple Pay, Credit Card, and Crypto in that order. This ranking indicates that customers favor digital wallets over traditional banking methods, with cryptocurrency being the least used.
   
* Top 5 Revenue-Generating Customers:
  
![top5](https://github.com/user-attachments/assets/fb8ed9e9-f9a1-42cb-b9ce-d74edd764422)

The analysis highlights the top five customers who contribute the most revenue to the business. These high-value customers are:

- CUST91885 – $4.46K
- CUST17138 – $4.44K
- CUST51767 – $4.37K
- CUST28324 – $4.30K
- CUST46222 – $4.04K
These customers are essential for business growth, as they drive significant revenue.

## GENERAL DASHBOARD
 
![GENERALDASHBOARD](https://github.com/user-attachments/assets/dcd367af-b6a2-4ad6-a09b-a4924f2f609a)


 ## INSIGHTS
- From the work performed, the buisness can leveraged on the peak months understand when customer demand is highest, allowing for optimized production, staffing, and supply chain management.
  
- Another insight suggests that women may have a higher engagement with the products or a greater purchasing frequency. Understanding this trend the  business can  tailor marketing strategies, personalize product recommendations, and optimize inventory to better cater to their dominant customer segment.
  
- Again,customers favor digital wallets over traditional banking methods, with cryptocurrency being the least used.  The Business can leverage this insight by optimizing checkout experiences, offering incentives for preferred payment methods, and ensuring seamless integration with PayPal and Apple Pay to enhance customer convenience.

- Meanwhie,for returning and consistent customers identifying and retaining them through loyalty programs, personalized offers, and premium customer service can further enhance their lifetime value and overall business profitability.

## CONCLUSIONS.

- Monthly sales data shows clear seasonal peaks, indicating that certain months consistently outperform others in terms of revenue.
- Female customers account for a higher share of purchases, and PayPal emerges as the most popular payment method.
- The revenue by region analysis reveals that certain geographic markets are outperforming others, indicating significant regional differences in market demand. Some regions consistently contribute more to the overall revenue, while others show potential for growth with targeted efforts.
  
## RECOMMENDATIONS
- Align marketing campaigns, product launches, and inventory planning with peak seasons to maximize sales.
- During off-peak periods, introduce targeted promotions or bundle offers to maintain steady revenue.
- Develop targeted marketing campaigns or loyalty programs for the dominant female segment to boost engagement.
- Ensure a seamless PayPal checkout experience and consider offering promotions for alternative payment methods to diversify payment usage.
- Enhance promotional activities and tailor marketing campaigns for high-performing regions to further capitalize on their momentum. 
- Investigate potential barriers in lower-performing regions and develop strategies—such as localized product offerings or region-specific pricing—to unlock growth opportunities.
- Align logistics and inventory management with regional demand patterns to improve efficiency and customer satisfaction.

## APPRECIATION 

![TY](https://github.com/user-attachments/assets/3f438f6a-343e-4212-8ae0-7a192d59cb52)

  Thank you for taking the time to explore this analysis. Your interest and engagement mean a lot, and I hope the insights provided help you gain a deeper understanding of the data and its impact. This project was driven by a passion for data storytelling, and I appreciate your support in this journey.

If you have any feedback, questions, or insights of your own, feel free to connect. Let's continue exploring the power of data together!

**Happy Analyzing! 🚀📊**
 







  

  



  








