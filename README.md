# Project Background

Elist Electronics, established in 2018, is a global e-commerce company that sells popular electronic products worldwide via its website and mobile app.

The company has significant amounts of data on its sales, marketing efforts, operational efficiency, product offerings, and loyalty program that has been previously underutilized. This project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve Elist’s commercial success.

Insights and recommendations are provided on the following key areas:

- **Sales Trends Analysis**: Evaluation of historical sales patterns, both globally and by region, focusing on Revenue, Order Volume, and Average Order Value (AOV).
- **Product Level Performance**: An analysis of Elist’s various product lines, understanding their impact on sales and returns.
- **Loyalty Program Success**: An assessment of the loyalty program on customer retention and sales.
- **Regional Comparisons**: An evaluation of sales and orders by region.

The cleaned dataset, along with all transformation and cleaning steps performed in Excel, can be found [here](https://github.com/Rohan-Morajkar/Elite-Electronics-Analysis/blob/main/Celan%20dataset.xlsx).

An interactive PowerBI dashboard can be downloaded [here](https://github.com/Rohan-Morajkar/Elite-Electronics-Analysis/blob/main/Elist%20Electronics%20Dashboard.pbix).

Targeted SQL queries regarding various business questions can be found [here](https://github.com/Rohan-Morajkar/Elite-Electronics-Analysis/blob/main/Buisness%20questions%20answered.sql).

# Data Structure & Initial Checks

Elist’s database structure as seen below consists of four tables: orders, customers, geo_lookup, and order_status, with a total row count of 108,127 records.

![Data structure](https://github.com/user-attachments/assets/5388ede8-c832-48f6-9137-306417caa099)

# Executive Summary

### Overview of Findings

After peaking in late 2020, the company’s sales have continued to decline, with significant drops in 2022. Key performance indicators have all shown year-over-year decreases: order volume by 40%, revenue by 46%, and average order value (AOV) by 10%. While this decline can be broadly attributed to a return to pre-pandemic normalcy, the following sections will explore additional contributing factors and highlight key opportunity areas for improvement.

Below is the overview page from the PowerBI dashboard and more examples are included throughout the report. The entire interactive dashboard can be downloaded [here](https://github.com/Rohan-Morajkar/Elite-Electronics-Analysis/blob/main/Elist%20Electronics%20Dashboard.pbix).

![Screenshot 2025-06-11 124915](https://github.com/user-attachments/assets/01f14c5a-6c59-4f89-9db1-718efff6c936)


 ### Sales Trends:

- **The company’s sales peaked in December 2020 with 4,019 orders totaling $1,251,721 monthly revenue.**  
  This corresponds with the boom in economy-wide spending due to pandemic-induced changing consumer behavior.

- Beginning in April 2021, **revenue declined on a year-over-year basis for 21 consecutive months.**  
  Revenue hit a company lifetime low in October 2022, with the company earning just over $178K. In the following months, revenue recovered slightly, following normal holiday seasonality patterns.

- Despite the downward trend, full-year 2022 remained above the pre-COVID 2019 baseline in all three key performance indicators.  
  This is primarily due to the stronger 1Q22, which recorded revenue and order count well above the same period in 2020, **up 37% and 23% respectively.**

- Average order value saw a one-month year-over-year increase in September 2022,  
  this can be attributed to an increased share of high-cost laptop orders.
  
![Screenshot 2025-06-11 125835](https://github.com/user-attachments/assets/f330cafb-e3bd-40b7-af82-7c45948219fd)

### Product Performance:

- **85% of the company’s orders are from just three products**, Gaming Monitor, Apple AirPods Headphones, and Samsung Charging Cable Pack. These three products accounted for $3.5M in revenue in 2022, 70% of the company’s total.

- In the headphones category, the Bose SoundSport Headphones have underperformed, contributing to less than 1% of total revenues and orders despite being, on average, $40 cheaper than the well-performing AirPods.

- The accessory category continues to grow as a share of orders, **now at 32% in 2022, up from 21% in 2020**. However, accessories remain less than 4% of total revenue.

- Regional revenue trends show that North America consistently led in performance, peaking around early 2020 with around $1M in monthly revenue. However, from early 2021 onward, all regions—including LATAM, EMEA, and APAC—experienced a steady decline

![Screenshot 2025-06-11 130416](https://github.com/user-attachments/assets/1ba4eea6-859f-4b6b-8b3a-7e09fef51651)


## Recommendations:

Based on the uncovered insights, the following recommendations have been provided:

- With 85% of orders and 70% of revenue coming from just three products, diversifying the product portfolio is crucial. **Expanding the accessory category with new product lines, particularly Apple charging cables, would provide upsell opportunities.**

- Despite the general sales success of Apple products, iPhone sales have been disappointingly low (1% of revenue in 2022). **Enhancing marketing efforts to previous Apple product buyers could boost sales.**

- Look to capitalize on the growing share of Samsung accessories (32% of order count in 2022) by **introducing higher-cost Samsung products in already carried product categories such as laptops and cellphones.**

- **Re-evaluate Bose SoundSport Headphones.** As the product has never made up more than 1% of annual revenue, attempt to sell through the product by implementing bundle offers and flash sales to non-Apple ecosystem loyalty members before discontinuing.

- **Continue and push forward the loyalty program.** In order to convert non-members, consider offering a one-time sign-up discount paired with increased general marketing of membership benefits and savings. Focus targeted and personalized ads to previous customers, and utilize past order data to increase marketing efforts when previously purchased products may need replacing.
