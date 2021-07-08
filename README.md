# PowerBI Dashboard E-commerce Transaction
## Overview
Iam processing the e-commerce transaction data from newcomers e-commerce platform to get some insights about the business. The example of the insights is the fact that transaction mostly happened between 10am to 15pm, therefore company can make some data-driven decisions like marketing campaign in that range of time. cause in this project focusing on data analytics, so the final output of this project is Power BI dashboard to be able share some insights to all stakeholders in the business.

## Dataset
The dataset is e-commerce transaction data with features or columns as follows:
1. invoice_no: invoice for every transaction in e-commerce.
2. invoice_date: the date for every transaction.
3. stock_code: the code for certain product.
4. description: the product details
5. unit_price: price for the product
6. quantity: quantity for product on certain transaction.
7. customer_id: customer information code in the company system.
8. province: location for the buyers.

## Data Cleaning
Cleaning the data and prepare dataset.
- Define unit_price and quantity to be greater than 0.
- Check the NAN data and data type.
- Transform null data in customer_id to 'no customer id'
- Transform invoice_date to datetime data type.
- Extract some date informations from invoice_date column.
- Define sales columns.

## Exploratory Data Analysis
Here some insights from the transaction data:
- There are some inclined sales, those are in the desember 2015, september 2016 and in november 2016. The data between those inclined events are tend to be constantly enough, no big inclined and declined. In December 2015, the inclined sales happend in the first day of the first week of the month and in December 2016 the inclined sales happend in seventh day of the first week of the month, this maybe happened cause customer shopping in case prepare for their holiday, or also can be there are year sale event in the e-commerce platform. In september 2016, the inclined sales happend in sixth day of the second week of the month.
- Surprisingly sunday is the least sales, with tuesday and thursday are the most sales in weeks.
- The trends for the customers to do the transaction are in operational hour which is 9 AM to 16 PM with 10 AM and 12 PM are the most sales happend and followed by 15 PM.
- The sales record in one transaction is invoice with no U541431 with nearly 1.2 milion Rupiah in one transaction.
- Top Products are dotcom postage, regency cakestand 3 tier, white hanging heart t--light holder with dotcom postage sales around 2.9 Millions Rupiah.
- The top location of sales transaction is DKI Jakarta.
- Invoice with no U573585 is transaction with the most variety products within one transaction.
- Products with more than 2000 transaction are white hanging heart t-light holder and Jumbo bag red retrosport.
- The top quantity of product in one single transaction is tea time tea towels. and from the plot we can see that none of the top quantity of the products in one transaction in top sales in products, meanwhile top transaction in products are more related to total sales in products.
- The top location for average sales every transaction are dominant by the location outside DKI Jakarta (assume HQ in Jakarta), this is because the delivery cost for far location tend to more expensive, so customers on those location tend to do big transaction all at once.

## Power BI dashboard
![](https://github.com/RodzanIskandar/PowerBI_dashboard_e-commerce_transaction/blob/main/images/ETD_dashboard.jpg)
![](https://github.com/RodzanIskandar/PowerBI_dashboard_e-commerce_transaction/blob/main/images/ETD_dashboard_product1.jpg)
