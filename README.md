# MedX-Pharma
Transformation of MedX Pharma flat file data into a normalized and structured data model and interactive dashboard design using Power BI.

![medx building](https://github.com/user-attachments/assets/1a48eac1-7295-45aa-b59a-60e3b169d774)



## Business Overview
**MedX Pharma** is a top pharmaceutical sales and distribution company with operations spanning several U.S. states. 
It collaborates with healthcare distributors, hospitals, and retail pharmacies to ensure the prompt delivery of premium-quality medications. 
The company oversees a diverse portfolio of pharmaceutical products, manages multiple warehouses, and partners with sales representatives and third-party distributors to broaden its market presence and meet growing demand.

## Problem Statement
The company is experiencing growing operational complexity due to an expanding product portfolio, a larger customer base, and increased sales activities across multiple regions. 
However, its reliance on flat Excel files for storing critical sales, customer, and distribution data has created challenges in performance monitoring and insight generation. 
The absence of a centralized data system and reporting solution prevents management from accurately identifying top-performing products, sales representatives, and regions, thereby limiting their ability to make timely, data-driven business decisions. 

## Project Aim
- This project aims to transform MedX Pharm’s flat file data into a normalized and structured data model using Power BI
- Build an interactive dashboard to analyze product sales, customer behavior and sales trend
- Enable data-driven decision-making and improve visibility into sales and distribution operations.

## Methodology
To transform the data, I:

✅ Cleaned and structured the dataset in Excel

✅ Extracted to Power BI’s Power Query 

✅ Transformed, and built a data model using fact and dimension tables (including a custom date dimension) and established connections via primary and foreign keys.

✅ Engineered calculated columns and DAX measures for advanced analytics

✅ Finally designed 3 interactive dashboards for strategic visibility and operational clarity
 

## Data Model

![MedX data Model](https://github.com/user-attachments/assets/5da1b399-08f5-4b93-821f-eb3a961e85d2)

## Dashboards
### (Click [(here)](https://app.powerbi.com/view?r=eyJrIjoiZTQ0NzJmYjItYmViZS00OGU3LWJmZWYtZjk4ZDVlOTVmMmM1IiwidCI6ImZmMGYzZTNhLTNlNTMtNDU0Zi1iMmI1LTZjNjg3NTNiOGVlNCJ9&embedImagePlaceholder=true&pageName=7a7cd65105bc46961040) to interact with Dashboards live)

![MedX 1](https://github.com/user-attachments/assets/492b8d92-2183-4f24-897c-907b865c1e6f)

![MedX2](https://github.com/user-attachments/assets/44e6fa41-4202-4ed8-aa63-b50ca8527d59)

![MedX33](https://github.com/user-attachments/assets/926d64b0-079b-4b86-9099-0265742422f5)

### (Click [(here)](https://app.powerbi.com/view?r=eyJrIjoiZTQ0NzJmYjItYmViZS00OGU3LWJmZWYtZjk4ZDVlOTVmMmM1IiwidCI6ImZmMGYzZTNhLTNlNTMtNDU0Zi1iMmI1LTZjNjg3NTNiOGVlNCJ9&embedImagePlaceholder=true&pageName=7a7cd65105bc46961040) to interact with Dashboards live)


## Key Performance Insights & Recommendations
### Customer Analysis

MedX recorded a strong performance in 2024, achieving a total revenue of **$12.21M**, with month-over-month (MoM) growth of **10.31%**. Previous month (PM) revenue stood at **$11.07M**. Sales volumes and orders also showed consistent growth, highlighting effective customer engagement and operational execution.

#### Revenue by Customer Type:
  
:small_blue_diamond: Clinics (27.9%) and Hospitals (27.5%) are the top contributors to revenue.

:small_blue_diamond: Wholesalers (23.7%) and Pharmacies (20.9%) follow.

#### Customer Base: 

:small_blue_diamond: Total Customers: 50

:small_blue_diamond: Distributors: 10

:small_blue_diamond: Average Discount: 7.4%

→ A relatively small but possibly high-value customer base with a moderate discount strategy.

#### Top Customers

:small_blue_diamond: Top 10 customers each generate $275K–$357K, accounting for a significant portion of revenue.

:small_blue_diamond: Top customer: Rivera with $357K revenue.

→ There seems to be heavy reliance on a few key clients.

#### Geographic Revenue Distribution

:small_blue_diamond: Michigan ($1.667M) and New York ($1,665M) generated the highest revenue. States like Nevada, Texas, Illinois, Montana, California, Arizona and Georgia also show strong engagement.

:small_blue_diamond: Several states show no activity — signaling large space for expansion.

### :bulb: Recommendations
1.	Expand Geographic Reach
Target underserved regions with focused marketing and distributor partnerships.
2.	Deepen High-Value Segments
Invest in clinics and hospitals (the highest revenue contributors) with tailored programs and offers.
3.	Top Customer Retention
Launch loyalty or VIP programs for top 10 customers to maintain and grow these accounts.
4.	Review Distributor Performance
Assess and optimize distributor effectiveness; explore potential additions in new regions.
5.	Optimize Discount Strategy
Ensure discount levels support profitability by analyzing margins by customer segment and region.
6.	Forecast Growth Strategically
Use current growth trends to set accurate sales and supply chain projections for 2025.

### Product Analysis 
#### Revenue Distribution

:small_blue_diamond: Antiseptics (26.93%) and Vaccines (21.81%) are the top product categories.

:small_blue_diamond: Antibiotics contribute the least at only 14.73%, suggesting lower demand or competition.

#### Warehouse Performance

:small_blue_diamond: Warehouse C handles 67.28% of orders, indicating high efficiency or capacity compared to Warehouse B (32.72%).

#### Top Products

:small_blue_diamond: Paracetamol leads with $343K, followed by Fluconazole at $324K  

#### Distributor Revenue

:small_blue_diamond: Johnson PLC leads with $1.38M in revenue, closely followed by Wagner and Nichols. 

:small_blue_diamond: The top 10 distributors perform within a comparable revenue range, indicating a balanced contribution across key partners.

### :bulb: Recommendations
1.	Investigate why Antibiotics underperform. Consider adjusting marketing or pricing strategies or discontinuing the product.
2.	Assess why Warehouse C handles most orders—consider scaling its operations or reallocating resources to Warehouse B for balance.
3.	Sales Rep Productivity: With 20 representatives handling 200 products, consider implementing product specialization or assigning reps by region to enhance efficiency.
4.	Reinforce relationships with top-performing distributors and introduce incentive programs to boost performance among mid-tier partners.


### Sales Trend 

:small_blue_diamond: Revenue fluctuates between $0.9M and $1.1M, with peaks in April, July and December, possibly due to seasonal trends or successful campaigns. A sharp dip occurs in June, suggesting a potential drop in demand or an operational issue.

:small_blue_diamond: October had the highest orders (454), while maximum cancellations were in November (167). All the months had substantial cancellations, indicating possible product availability issues or customer dissatisfaction. 

:small_blue_diamond: A consistent number of pending orders each month suggests potential delays in fulfillment, an area for improvement in logistics.

:small_blue_diamond: David Cox is the top performer with $704K revenue and 273 orders—his strategies could be analyzed and leveraged to boost team performance. Robert Bauer, at the bottom with $520K revenue and 228 orders, may need targeted coaching or motivation.

### :bulb: Recommendations
1. Boost June Sales: Identify reasons for the slump and introduce discounts or targeted promotions to counteract it.
2. Reduce Cancellations: Investigate common cancellation reasons and refine inventory management or customer engagement.
3. Optimize fulfillment processes to lower pending orders and improve delivery speed.
4. Empower Low Performers: Offer training, mentorship, or incentives to encourage growth and improve sales rep productivity.


## :round_pushpin: Conclusion
**MedX** demonstrated a solid performance in **2024**, achieving strong revenue growth, consistent sales volumes, and high engagement across key customer segments. Clinics and hospitals were the primary revenue drivers, supported by a small but valuable customer base. However, there remains untapped potential in underserved geographic regions and among mid-tier customer types.
Operationally, there are clear opportunities to boost efficiency—especially in sales rep deployment, warehouse load balancing, and order fulfillment. Strategic refinement in distributor partnerships, discount management, and product focus (especially underperforming categories like antibiotics) will be critical to sustaining growth.
To maintain momentum into **2025**, MedX should focus on geographic expansion, deepen relationships with top clients and high-value customer segments, optimize internal operations, and use data-driven forecasting to align inventory and sales targets. With the right strategic adjustments, MedX is well-positioned to scale its impact and profitability across a broader market.
 
![Thank you](https://github.com/user-attachments/assets/4fdea15a-1789-4149-8a75-088cdae7f530)







