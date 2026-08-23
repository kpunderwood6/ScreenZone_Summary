<img width="3000" height="900" alt="Background Logo 2026" src="https://github.com/user-attachments/assets/195e96d7-fc22-488f-a85a-e5778460b2ad" />

<div align="center">
	
# E-Commerce Performance Report

</div>

<div align="center">

## Client Background 
</div>

**Screen Zone** is a global e-commerce company founded in 2018 selling popular electronics products. Expanding globally, tapping into multiple marketing channels, increasing their product offering, and a consistently competitive market developed a new need to understand their presence in the e-commerce market. 

From 2019-2022, the company amassed over **$28M** in sales from **87K** customers spending approximately **$260** per order. The current data spans multiple measures and dimensions including sales, regions, products, marketing channel, and customer loyalty.

<div align="center">
	
## Project Goals

</div>

An in-depth analysis was completed to determine **Screen Zone's** performance and gather insights for multiple teams to make strategic decisions, change course if needed, and build on any strong, consistent indicators. 

This analysis reviews the following key **North Star Metrics:**

+ **Sales Trends:** Analyzing sales, total number of orders, and average order value (AOV).
+ **Region Analysis:** Determining each region's contribution to sales to prioritize strong performers and develop potential.
+ **Product Performance:** Determining the best performing products to optimize the product line.
+ **Marketing Analysis:** Evaluating current marketing channels to steer new development.
+ **Loyalty Program:** Assessing the success of the current loyalty program.
+ **Customer Acquisition:**  Understanding the company’s customer acquisition lifecycle.
+ **Recommendations:** Providing recommendations based on deep dive insights.

<div align="center">
	
# Data Structure and Quality
</div>

<div align="center">
	
## Entity Relationship Diagram
</div>

Screen Zone’s database structure consists of four tables: orders, customers, geo_lookup, and order_status.

<img width="1352" height="928" alt="image" src="https://github.com/user-attachments/assets/4a39fae1-5313-44f3-8292-bd24fcc11c8d" />

<div align="center">

## Data Quality 

</div>
The dataset contained instances of missing and erroneous data. The table below shows the magnitude of the inconsistencies that could not be resolved during the data cleaning process, and require collaboration with the appropriate team to correct.

<img width="850" height="20" alt="image" src="https://github.com/user-attachments/assets/11f46558-505d-4ddd-a8b0-412013f24e9f" />
<img width="1330" height="375" alt="image" src="https://github.com/user-attachments/assets/c6621649-e484-4bf4-a360-6819c6aba490" />

| Table | Field | Issue | Row Count | Magnitude|
|---|---|---|---:|---:|
|Customers|	country_code|Missing Values	|140|0.13%|
|Customers|	country_code|Country codes identified as "A1" and "EU"|19|0.02%|
|Orders|currency|Missing Values|54|0.05%|
|Orders|local_price|$0.00 price points|158|0.15%|
|Orders|purchase_ts|Purchase Date is after Ship Date|15|0.01%|
|Orders|usd_price|$0.00 price points|158|0.15%|
|Orders|usd_price|Missing Values|33|0.03%|


<div align="center">
	
# Insights Summary
</div>

+ __Sales Growth and Peak Performance__
	* 2020 returned the highest total sales of $10.2M, a 163% year-over-year increase.
	* Growth declined in 2021, but generated a solid $9.1M.
+ __Downward Trend to Pre-Pandemic Levels__
	* 2022 sales growth decreased by 46% marking a return toward pre-pandemic levels, but still outperformed 2019 by $1M.
	* Q4 2022 recorded an unprecedented 72% year-over-year decrease.
+ __Quarterly Insights & Seasonal Trends__
	* Q3 and Q4 generally show strong performance likely due to back-to-school and holiday season shopping.
	* Average order value was higher in Q3 and Q4 than in Q1 and Q2 every year confirming consistent seasonal demand. 
+ __Recommendations__
	* Further investigate the steep decline in 2022 total sales specifically Q4.
	* Continue to invest in and highlight high performing products.
	* Diversify the product mix to include more moderately priced products potentially reducing dramatic sales fluctuations.
	* Prioritize developing additional marketing channels to reduce dependency on direct marketing.

<div align="center">

# Deep Dive Insights
</div>

<div align="center">
	
## Sales Trends 
</div>

<img width="1331" height="651" alt="image" src="https://github.com/user-attachments/assets/bad352ff-c12e-4373-ab2a-a1d5754326e2" />

+ __COVID-19 pandemic surged 2020 sales as customers pivoted to online purchasing.__
	* 2020 returned a remarkable revenue best of $10.2M, a 163% YoY increase from $3.8M in 2019.
	* Orders doubled in 2020 with AOV increasing 31% to its peak of $300 from $230. 
	* This growth, ultimately impermanent, was a direct result from the Covid-19 pandemic.
+ __2021 saw momentum dip, but still returned $9.1M in revenue.__ 
	* 2021 saw a slight 10% decrease YoY, a $1M contraction from 2020. 
	* Order count peaked in 2021 at 36K, but AOV decreased to $254 demonstrating a decline in spending. 
+ __Sales continued to decrease in 2022 to pre-COVID levels.__
	* Sales continued to decline with a 46% YoY decrease in 2022 of $4.1M. 
	* 2022 orders were 1.3 times more than 2019 resulting in revenue that surpassed 2019 by $1M; however, both years returned an AOV of $230.
	* The matching AOV confirms a return to what is likely Screen Zone’s customers spending baseline.

<img width="1330" height="649" alt="image" src="https://github.com/user-attachments/assets/b87b0a75-b9a6-4202-abbf-1516306745c8" />

+ __H2 drives total sales in comparison to less profitable H1.__
	* Q4 to Q1 and Q1 to Q2 QoQ sales decreased every year except quarters that aligned with the pandemic.  This decrease echoed in MoM sales as well from December to January and January to February. 
	* Q2 to Q3 and Q3 to Q4 QoQ sales increased every year except 2022 and a minor 1% decrease from Q3 2021 to Q4 2021. This momentum was disrupted due to September to October MoM decreases every year with a high of 55% in 2022, a $220K drop; however, sales increased MoM from October to November and from November to December every year.
	* The momentum of increased sales from Q2 to Q3 and Q3 to Q4 aligned with back-to-school and holiday season shopping with a window of fatigue directly after back-to-school and before holiday season. 
+ __Average Order Value__ 
	* After a four-quarter increase in 2020, AOV decreased YoY for the following eight quarters. 
	* Over the four years, AOV was higher the second half of the year, Q3 ($261) and Q4 ($265) then in the first half, Q1 ($258) and Q2 ($255) confirming consistent seasonal demand.  
+ __H2 had both the best and worst performing quarter.__
	* Q4 2020 returned the highest sales of $3M from a 158% YoY increase from Q4 2019.
	* Two years later Q4 2022 saw the highest YoY decrease of 72% returning the lowest quarterly sales of $649K. This was an unprecedented contraction considering Q4 was consistently one of or the best performing quarter compared to other quarters in the same year. 

<img width="1332" height="208" alt="image" src="https://github.com/user-attachments/assets/93e69a69-13ee-4c9e-99eb-6152de961965" />

+ __Q4 2022 experienced a steep decline in new customer acquisition.__
	* H2 2022 saw a 38% sales decline from H1 2022.
	* New customers decreased by 41% from 2021 into 2022. The decline continued with a Q3 2022 to Q4 2022 50% decrease in new customers.
	* This highlighted an acquisition problem being a contributor to the high YoY sales decrease for Q4 2022 and not only customers generally ordering less expensive products.  

<div align="center">

## Region Analysis
</div>

<img width="1337" height="655" alt="image" src="https://github.com/user-attachments/assets/2af2ad39-c508-4844-be2b-e68bdc2f3180" />
<img width="1009" height="209" alt="image" src="https://github.com/user-attachments/assets/bf6a844e-c8fb-470b-a30c-c60b8ae906ef" />

<div align="center">
	
## Product Performance
</div>

<img width="1333" height="739" alt="image" src="https://github.com/user-attachments/assets/29d49ff6-a8df-4e44-a91a-482ffa91d131" />
<img width="1160" height="610" alt="image" src="https://github.com/user-attachments/assets/603c0193-b1c8-41a0-af5d-531b5efe3072" />


<div align="center">
	
### Return Rates ###
</div>

+ The overall return rate for the four-year period was approximately 5%.
+ 2020 had the highest return rate of 9% dropping to 0% in 2022. This 0% rate is either due to missing data or the return policy, but must be confirmed. 
+ Premium products were returned at much higher rates. 
	* The MacBook Air Laptop and the ThinkPad Laptop were consistently the most returned products each year with the Apple iPhone and 27in 4K Gaming Monitor alternating for third and fourth place.
	* The MacBook Air Laptop had the highest product return rate of 18% in 2019, but each year it decreased.
	* Loyalty members did not return MacBook Air Laptops, a notable difference between members and non-loyalty members. 
+ Non premium products recorded return rates of 3% or less.
<img width="1332" height="650" alt="image" src="https://github.com/user-attachments/assets/fa1ac367-b832-4d15-b1f0-0f029ae7403b" />

<div align="center">
	
## Marketing Analysis
</div>

<img width="1335" height="482" alt="image" src="https://github.com/user-attachments/assets/000f1f71-95d3-42c3-817e-79d35b9daa42" />

+ Direct marketing was the primary force in generating sales across all regions averaging 83% of total sales. Although, there has been a YoY decline starting at 86% to 76%. 
+ Email marketing’s share of total sales increased each year reaching 16% in 2022 doubling from 8% in 2019. Email was more successful in LATAM and NA with 13% of sales from those campaigns whereas APAC saw 11% and EMEA saw 9%.
+ Affiliate marketing performed better within NA at 4% and EMEA at 3%, but in LATAM and APAC it returned approximately 1%.
+ Social Media marketing consistently yielded minimal results across all regions. 

<div align="center">
	
## Loyalty Program 
	
</div>

<img width="1331" height="462" alt="image" src="https://github.com/user-attachments/assets/b6652b38-5a3a-4379-af44-b6f01a8328d4" />

+ Total sales from loyalty program members grew 614% in 2020 starting at $415K in 2019, with continued growth of 64% in 2021, but saw a 44% decrease in 2022.
+ The AOV for non-members dropped from $345 in 2020 to $214 in 2022. The loyalty members AOV started at $228 in 2019 increased to $249 and only dropped to $245, much less fluctuation than non-members. 
+ Loyalty program members generated more orders in 2021 and 2022 than non-members. 
+ Only 35% of returning customers were loyalty program members. Given that customers are mostly returning to purchase the gaming monitor and headphones, ideally there would be more returning customers in the loyalty program. 

<div align="center">
	
## Customer Acquisition
</div>

+ Customers on average waited 92 days to make their first order after creating an account. 
+ Customers acquired through affiliate marketing placed their first order within an average of 5 days, but direct marketing recorded approximately 89 days.  
+ Even though affiliate marketing only contributed 3% of total sales, it is important to highlight affiliate marketing converted potential customers to their first purchase in an average of 5 days, the fastest conversation rate of all channels.


<div align="center">
	
## Recommendations 

</div>
Recommendations for Screen Zone based on deep dive insights:

### Marketing Strategy

+ Prioritize developing other marketing channels to attract new customers and reduce current overreliance on direct marketing.  
	* Prioritize investment in targeted email campaigns aligning with seasonal trends to capitalize on back-to-school and holiday season peak sales.
	* Strengthen current affiliate partnerships and prioritize developing additional partnerships. The short customer acquisition journey discovered within the affiliate marketing channel demonstrates potential for further success. 
	* Invest in further developing social media strategies due to their low performance.
+ Explore region specific targeted marketing across regions prioritizing APAC and LATAM. 
	* APAC has untapped potential considering its high AOV. 
	* LATAM has the greatest potential for increased sales. 
+ Since 17% of customers ordered through the mobile app, an opportunity exists for increased marketing with notifications for discounts, app specific promotional deals, and advertising the loyalty program. 

### Products

+ Continue to invest in and highlight high performing products.
	* 27in 4K Gaming Monitor performed particularly well each September. Shift focus to heavily market this product during the back-to-school season and ensure product placement is always prominent on the website. 
	* ThinkPad Laptop showed more consistent growth of any product between February 2022 and October 2022. Promotions and marketing should capitalize on the high product AOV.
+ Consider bundling premium products with non-premium products. 
	* The MacBook Air Laptop and Apple AirPods Headphones are prime candidates for bundling. 
+ Diversifying the product mix to include more moderately priced products could reduce dramatic fluctuations in total sales by decreasing reliance on the volume of premium product sales. 
+ Consider deprioritizing or phasing out specific products due to low sales.
	* Bose Headphones and Samsung Webcam combined contributed approximately only 1% of sales. 
	* The Apple iPhone sales were surprisingly low (1%) considering its place as a premium product in an electronic product line. The product stock should be investigated to understand if particular models were possibly not attractive to customers or if they were priced incorrectly.
+ Investigate current quality control practices and reevaluate the current return window for products. 

### Loyalty Program

+ Given its growth the first two years and higher total sales the last two, the loyalty program should receive continued investment with close monitoring.
+ Prioritize converting repeat customers into loyalty members with targeted marketing of membership benefits and savings.  
+ Offer incentives to members who have only purchased non-premium products. 
