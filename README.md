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

# Insights Deep Dive
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

+ __H2 generally outperformed H1 in total sales.__
	* Quarter-over-quarter sales declined from Q4 to Q1 and Q1 to Q2 each year, a pattern that also appeared month-over-month from December through February. This trend was generally consistent with the exception of 2020 where pandemic-driven demand disrupted this pattern.
	* Q2 to Q3 and Q3 to Q4 sales increased every year except 2022 and a minor 1% decrease from Q3 2021 to Q4 2021. This upward momentum was interrupted by a recurring September to October decrease each year reaching as high as 55% in 2022; however, sales recovered month-over-month from October through December each year.
	* This H2 pattern aligns with back-to-school and holiday season shopping with the September to October dip suggesting a potential period of softened demand between the two seasons.
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
<img width="1332" height="652" alt="image" src="https://github.com/user-attachments/assets/eab45a05-34aa-4e6b-b079-766f4b26b96c" />

+ __North America and Europe, Middle East, and Africa were the top performing regions.__
	* North America averaged 52% of total sales peaking at 55% in 2022.
	* EMEA ranked second averaging 29% of total sales and peaked at 30% in 2021.
+ __Average Order Value Performance__
	* Although APAC ranked third in overall sales, its AOV was higher than North America’s each year from 2020-2022 peaking at $317 in 2020.
	* APAC also recorded the highest AOV over the four-year period of $279 compared to North America’s $260.
	* While total sales declined back to pre-pandemic levels in 2022, APAC and EMEA still generated higher AOVs in 2022 than 2019, but LATAM and North America’s AOVs dropped below their 2019 baseline.
+ __Regional Callout__
	* In LATAM, sales have underperformed averaging only 6% of total sales with a $625K total sales peak in 2020. 

<div align="center">
	
## Product Performance
</div>

<img width="1333" height="739" alt="image" src="https://github.com/user-attachments/assets/29d49ff6-a8df-4e44-a91a-482ffa91d131" />

+ __Top Performers__
	* The 27in 4K Gaming Monitor ranked as the top performing product generating $9.8M in total sales across all four years.
	* Apple AirPods Headphones received the most orders and recorded $7.7M in total sales.
	* MacBook Air Laptop ranked third with $6.38M in total sales and the highest AOV of $1,588.
	* ThinkPad Laptop ranked fourth returning $3.2M in total sales despite having the second highest AOV of $1,100.
+ __Key Indicators__
	* Premium product sales drove 2020 growth with MacBook Air Laptop sales increasing 384% and ThinkPad Laptop sales increasing 222%. This level of growth was not sustainable becuase both products declined significantly in 2021 while lower-priced products like the Samsung Webcam grew 134%.
	* 20% of customers returned to make another purchase with 76% of those repeat purchases comprised of the 27in 4K Gaming Monitor and Apple AirPods Headphones.
+ __Brand Surprises__
	* Apple experienced a notable contrast between products. The AirPods Headphones were the most ordered product, but the Apple iPhone generated only $213K in total sales, which is unusually low for an Apple product in an electronics line.
	* The Samsung Webcam, which received zero orders in 2019, outperformed the Apple iPhone by $150K. In addition, loyalty program members did not purchase the Apple iPhone during the four-year period.

<div align="center">
	
### Return Rates ###
</div>

+ The overall return rate for the four-year period was approximately 5%.
+ 2020 had the highest return rate of 9% dropping to 0% in 2022. This 0% rate is either due to missing data or the return policy, but must be confirmed. 
+ Premium products were returned at much higher rates. 
	* The MacBook Air Laptop and the ThinkPad Laptop were consistently the most returned products each year with the Apple iPhone and 27in 4K Gaming Monitor alternating for third and fourth place.
	* The MacBook Air Laptop had the highest product return rate of 18% in 2019, but each year it decreased.
	* Loyalty members did not return MacBook Air Laptops, a notable difference between members and non-loyalty members. 
+ Non-premium products recorded return rates of 3% or less.
<img width="1332" height="650" alt="image" src="https://github.com/user-attachments/assets/fa1ac367-b832-4d15-b1f0-0f029ae7403b" />

<div align="center">
	
## Marketing Analysis
</div>

<img width="1335" height="482" alt="image" src="https://github.com/user-attachments/assets/000f1f71-95d3-42c3-817e-79d35b9daa42" />

+ Direct marketing was the primary driver of sales across all regions averaging 83% of total sales over the four-year period.
+ Email marketing grew each year reaching 16% of total sales in 2022, up from 8% in 2019. Performance varied by region with LATAM and North America leading at 13% of sales from email campaigns followed by APAC at 11% and EMEA at 9%.
+ Affiliate marketing performed strongest in North America at 4% and EMEA at 3%, while LATAM and APAC each recorded approximately 1%. Nonetheless, affiliate marketing recorded the highest AOV at $303 suggesting it tends to attract higher-spending customers.
+ Social media marketing averaged 1% of total sales over the four-year period consistently yielding minimal results across all regions.
+ Orders without an identified marketing channel saw significant spikes, growing 1,493% in 2020 and 368% in 2022.

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
+ Even though affiliate marketing only contributed 3% of total sales, it is important to highlight affiliate marketing converted potential customers to their first purchase in an average of 5 days, which was the fastest conversation rate of all channels.


<div align="center">
	
## Recommendations 

</div>
Recommendations for Screen Zone based on deep dive insights:

### Marketing Strategy

+ Prioritize developing other marketing channels to attract new customers and reduce current over reliance on direct marketing.  
	* Prioritize investment in targeted email campaigns aligning with seasonal trends to capitalize on back-to-school and holiday season peak sales.
	* Strengthen current affiliate partnerships and prioritize developing additional partnerships. The short customer acquisition journey and high AOV discovered within the affiliate marketing channel demonstrates potential for further success. 
	* Invest in further developing social media strategies due to their low performance.
+ Explore region specific targeted marketing across regions prioritizing APAC and LATAM. 
	* APAC has untapped potential considering its high AOV. 
	* LATAM has the greatest potential for increased sales. 
+ Since 17% of customers ordered through the mobile app, an opportunity exists for increased marketing with notifications for discounts, app specific promotional deals, and advertising the loyalty program. 
+ Identify and resolve the source of orders without an attributed marketing channel to capture accurate channel performance.
  
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
