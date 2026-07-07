<img width="3000" height="900" alt="Background Logo 2026" src="https://github.com/user-attachments/assets/195e96d7-fc22-488f-a85a-e5778460b2ad" />

<div align="center">
	
# E-Commerce Performance Report

</div>

<div align="center">

## Client Profile 
</div>

**Screen Zone** is a global e-commerce company founded in 2018 selling popular electronics products. Expanding globally, tapping into multiple marketing channels, increasing their product offering, and a consistently competitive market developed a new need to understand their presence in the e-commerce market. 

From 2019-2022, the company amassed over **$28M** in sales from **87K** customers spending approximately **$260** per order. The current data spans multiple measures and dimensions including sales, regions, products, marketing channel, and customer loyalty.

<div align="center">
	
## Project Goals

</div>

An in-depth analysis was completed to determine **Screen Zone's** performance and gather insights for multiple teams to make strategic decisions, change course if needed, and build on any strong, consistent indicators. 

This analysis reviews the following key **NorthStar Metrics:**

+ **Sales Trends:** Analyzing sales revenue, total number of orders, and average order value (AOV).
+ **Region Analysis:** Determining each region's contribution to sales revenue to prioritize strong performers and develop potential.
+ **Product Performance:** Determining best performing products to optimize the product line.
+ **Marketing Analysis:** Evaluating current marketing channels to steer new development.
+ **Loyalty Program:** Assessing the success of the current loyalty program.
+ **Customer Acquisition:**  Understanding the company’s customer acquisition lifecycle.
+ **Recommendations:** Providing recommendations based on deep dive insights.

<div align="center">
	
# Data Structure
</div>

<div align="center">
	
## Entity Relationship Diagram
</div>

Screen Zone’s database structure consists of four tables: orders, customers, geo_lookup, and order_status.

<img width="1352" height="928" alt="image" src="https://github.com/user-attachments/assets/4a39fae1-5313-44f3-8292-bd24fcc11c8d" />


| Table | Field | Issue | Row Count | Magnitude
|---|---|---|
|Customers|	country_code|Missing Values	|140|0.13%|
|Customers|	country_code|Country codes identified as "A1" and "EU"|19|0.02%|
|Orders|currency|Missing Values|54|0.05%|
|Orders|local_price|$0.00 price points|158|0.15%|
|Orders|purchase_ts|Purchase Date is after Ship Date|15|0.01%|
|Orders|usd_price|$0.00 price points|158|0.15%|
|Orders|usd_price|Missing Values|33|0.03%|




<div align="center">
	
# Executive Summary
</div>

After peaking in **2020 from a 163% year-over-year increase**, Screen Zone's sales entered a prolonged decline ending in a particularly steep drop in Q4 2022. Despite a strong start in January 2021, **downward trends persisted through 2022** across all key performance indicators: a **46%** year-over-year decrease in total sales, a **10%** year-over-year decrease in average order value, and a **40%** year-over-year decrease in order count. While 2022 marked a return toward pre-pandemic levels, it still outperformed 2019 by **$1M**. The following sections explore NorthStar Metrics in detail and highlight opportunities for improvement.

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
	* Sales continued to decline with a 46% YoY decrease in 2022 of $4.1M 
	* 2022 orders were 1.3 times more than 2019 resulting in revenue that surpassed 2019 by $1M; however, both years returned an AOV of $230.
	* The matching AOV confirms a return to what is likely Screen Zone’s customers spending baseline.

<img width="1330" height="649" alt="image" src="https://github.com/user-attachments/assets/b87b0a75-b9a6-4202-abbf-1516306745c8" />

+ __H2 drives total sales in comparison to less profitable H1.__
	* Q4 to Q1 and Q1 to Q2 QoQ sales decreased every year except quarters that aligned with the pandemic.  This decrease echoed in MoM sales as well from December to January and January to February. 
	* Q2 to Q3 and Q3 to Q4 QoQ sales increased every year except 2022 and a minor 1% decrease Q3 2021 to Q4 2021 QoQ. This momentum would see a disruption of September to October MoM decreases every year with a high of 55% in 2022, a $220K drop; however, sales increased MoM from October to November and from November to December every year.
	* The momentum of increased spending from Q2 to Q3 and Q3 to Q4 aligned with seasonal Back to School and Holiday Season shopping with a window of fatigue directly after Back to School and before Holiday Season. 
+ __Average Order Value__ 
	* After a four-quarter growth increase in 2020, AOV decreased YoY for the following eight quarters. 
	* Over the four years, AOV was higher in second half of the year, Q3 ($261) and Q4 ($265) then in the first half, Q1 ($258) and Q2 ($255) confirming seasonal spending. 
+ __H2 had both the best and worst performing quarter.__
	* Q4 2020 returned the highest revenue of $3M from a 158% increase from Q2 2019 YoY.
	* Two years later Q4 2022 saw the highest YoY decrease of 72% returning the lowest quarterly sales of $649K. This was an unprecedented contraction considering Q4 was consistently one of or the best performing quarter comparted to other quarters in the same year. 

<img width="1332" height="208" alt="image" src="https://github.com/user-attachments/assets/93e69a69-13ee-4c9e-99eb-6152de961965" />

+ __Potential customer Acquisition problem and not only an AOV decrease.__
	* H2 2022 saw a 38% sales decline from H1 2022.
	* New Customers decreased by 41% from 2021 into 2022. The decline continued with a Q3 2022 to Q4 2022 decrease of 50% in new customers.
	* This highlighted an acquisition problem being a contributor to the high YoY sales decrease for Q4 2022 and not only customers generally purchasing less expensive products.  

<div align="center">

## Region Analysis
</div>

<img width="1337" height="655" alt="image" src="https://github.com/user-attachments/assets/2af2ad39-c508-4844-be2b-e68bdc2f3180" />
<img width="1010" height="193" alt="image" src="https://github.com/user-attachments/assets/a86e34a1-a5b4-458e-af40-d2c7e6ad167e" />

<div align="center">
	
## Product Performance
</div>

<img width="1333" height="739" alt="image" src="https://github.com/user-attachments/assets/29d49ff6-a8df-4e44-a91a-482ffa91d131" />
<img width="1053" height="537" alt="image" src="https://github.com/user-attachments/assets/8b4c07b8-5433-4c9d-bdfb-935eb2457489" />

<div align="center">
	
### Return Rates ###
</div>

+ The overall return rate for the four-year period was approximately 5%.
+ 2020 had the highest return rate of 9% dropping to 0% in 2022. This 0% rate is either due to missing data or the return policy, but must be confirmed. 
+ Premium products were returned at much higher rates. 
	* The MacBook Air Laptop and the ThinkPad Laptop were consistently the most returned products each year with the Apple iPhone and 27in 4K Gaming Monitor alternating for third and fourth place.
	* The MacBook Air Laptop had the highest product return rate of 18% in 2019, but each year it decreased.
	* Loyalty members did not return a MacBook Air Laptops, a notable difference between members and non-loyalty members. 
+ Non premium products saw return rates of 3% or less.
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
+ Affiliate marketing saw customers making their first order on average within 5 days. It was approximately 89 days for direct marketing. 
+ Even though affiliate marketing only contributed 3% of total sales, it is important to highlight the channel saw a significantly higher turnaround in customer acquisition from potential customer to account creation to first purchase. 

<div align="center">
	
## Recommendations 

</div>
Recommendations for Screen Zone based on deep dive insights:

### Marketing Strategy

+ Prioritize developing other marketing channels to attract and reduce current overreliance on direct marketing.  
	* Prioritize investment in targeted email campaigns and align them with seasonal trends to capitalize on back-to-school and holiday season peak sales.
	* Strengthen current affiliate partnerships and develop more partnerships. The short customer acquisition journey discovered within the affiliate marketing channel demonstrated potential for further success. 
	* Invest in further developing social media strategies due to their low performance.
+ Explore region specific targeted marketing across regions prioritizing APAC and LATAM. 
	* APAC has untapped potential considering its high AOV. 
	* LATAM has the greatest potential for increased sales. 
+ Since 17% of customers ordered through the mobile app, an opportunity exists for increased marketing with notifications for discounts, app specific promotional deals, and advertising the loyalty program is important. 

### Products

+ Continue to invest in and highlight high performing products.
	* 27in 4K Gaming Monitor performed particularly well each September. Shift focus to heavily market this product during the back-to-school season and ensure product placement is always prominent on the website. 
	* ThinkPad Laptop showed more consistent growth of any product between February 2022 and October 2022. Promotions and marketing should capitalize on the high product AOV.
+ Consider bundling premium products with non-premium products. 
	* Bose Headphones and Samsung Webcam are prime candidates for product bundles and add-on deals at customer checkout. 
	* The MacBook Air Laptop and Apple AirPods Headphones are also candidates for budling. 
+ Diversifying the product mix to include more moderately priced products could reduce dramatic fluctuations in total sales by decreasing reliance on the volume of premium product sales. 
+ Consider deprioritizing or phasing out specific products due to low sales.
	* Bose Headphones and Samsung Webcam combined contributed approximately only 1% of sales. 
	* The Apple iPhone sales were surprisingly low (1%) considering its place as a premium product in an electronic product line. The product stock should be investigated to understand if particular models were possibly not attractive to customers or if they were priced incorrectly.
+ Investigate current quality control practices and reevaluate the current return window for products. 

### Loyalty Program

+ The loyalty program should remain and receive continued investment as it saw high growth in its first two years and in the last two years returned higher total sales than non-members.
+ Prioritize converting repeat customers into loyalty members with targeted marketing of membership benefits and savings.  
+ Offer incentives to members who have only purchased non-premium products. 
