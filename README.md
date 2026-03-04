# 📊 Mobile Phone Sales Performance Analysis

### Executive Sales Intelligence Dashboard | Built in Microsoft Excel
<img width="1600" height="900" alt="Hafsoh&#39;s Design (3) (1)" src="https://github.com/user-attachments/assets/c4515c71-e5f8-4afc-8619-22700dc3d475" />

## 🔎 Project Overview

The Mobile Phone Sales Performance Analysis project is a comprehensive executive dashboard built in Microsoft Excel using Power Pivot and the Data Model to transform 
transactional sales data into strategic business intelligence.

This solution provides senior management with structured visibility into:

* Revenue growth trends
* Profitability efficiency
* Brand and distributor dominance
* Market concentration risk
* Seasonal performance behavior
* Pricing effectiveness

The analysis moves beyond basic reporting and focuses on answering a central strategic question:

## 🏢 Business Context

The company operates in the mobile phone distribution industry, selling multiple brands across different countries through various distributors and telecom operators.

Despite strong sales activity, management faced several operational blind spots:

* No centralized visibility into revenue and profit performance
* Inability to identify dominant brands or distributors
* No structured YoY or quarterly growth tracking
* Limited understanding of pricing efficiency
* Unclear seasonal and weekday sales behavior
* No measurement of market concentration risk

These gaps limited data-driven strategic planning and risk management.

## 🎯 Business Objectives

The objective of this project was to design an executive dashboard that:

* Tracks total revenue, cost, profit, and volume performance
* Measures profitability and pricing efficiency
* Identifies top revenue, volume, and profit drivers
* Evaluates distributor and operator performance
* Detects seasonal sales patterns
* Quantifies market concentration risk
* Supports strategic expansion and pricing decisions

❓ Business Questions Answered
Revenue & Growth

* What is total revenue by year?
* Which quarter performs best?
* Is revenue growing year-over-year?

Profitability

* Which brand generates the highest profit?
* Which country has the lowest margin?

Distribution

* Which distributor sells the most units?
* Which distributor contributes most profit?

Seasonality

* Which months drive highest sales?
* Are weekends stronger than weekdays?

Strategic

* Should expansion focus on specific countries?
* Which brands deserve increased marketing investment?

## 🗂 Data Model & Structure

### Fact Table: Phone Sales Table

* Date
* Country
* Distributor
* Brand
* Operator
* Unit Cost
* Amount (Total Cost)
* Unit Price
* Revenue
* <img width="745" height="251" alt="Phone Sales 1" src="https://github.com/user-attachments/assets/16568d2b-b436-4be6-9873-ead2e38caa98" />


### Date Dimension: Date_Phones Table

* Year
* Quarter
* Month
* Month Name
* Month & Year
* Week Day
* Day Name
* Week Number
* Quarter (Q)
* Date
<img width="656" height="251" alt="Phone Sales 2" src="https://github.com/user-attachments/assets/4ea6ba81-bf59-491e-8853-bc871aabeef5" />

### Dax Measures Created
<img width="599" height="353" alt="Phone Sales Dax" src="https://github.com/user-attachments/assets/30e73031-d5b5-4ab5-905b-3a7e91895552" />

### Data Modelling
The dataset was structured using a star schema design inside Excel’s Data Model, enabling:

* Time intelligence analysis
* Relationship-based calculations
* Advanced measure creation
* Scalable performance reporting

<img width="392" height="356" alt="Phone Sales Model" src="https://github.com/user-attachments/assets/67a4726d-ace6-4dd2-be82-4f45202918f7" />

## 📈 Dashboard 1

### Business Performance Overview — Are We Growing Sustainably?
<img width="8192" height="5121" alt="Salesphone1" src="https://github.com/user-attachments/assets/37851da4-322f-41f8-ba12-144b22e37c34" />

#### KPIs
* Total Revenue: $63.60M
* Total Cost: $41.39M
* Total Profit: $22.21M
* Total Units Sold: 76,172
* Profit Margin: 36.19%

#### Key Insights

* Revenue and profit peaked in 2021 ($25.16M revenue; $8.76M profit).
* 2020 recorded the lowest performance, indicating recovery trend.
* Q3 is consistently the strongest performing quarter.
* Apple generates the highest revenue ($16.07M).
* LG dominates in unit volume (19,891 units).
* Tottus is the leading distributor ($18.30M revenue).

#### Strategic Implication

The business demonstrates strong growth recovery and healthy margins, but performance is highly brand and distributor dependent.

## 📊 Dashboard 2

### Profitability & Pricing Intelligence — Are We Operating Efficiently?
<img width="8192" height="5121" alt="salesphone2" src="https://github.com/user-attachments/assets/c1cf00a2-307c-423d-9f23-bb231de34f9b" />

#### KPIs

* Average Selling Price: $835
* Average Unit Cost: $543
* Profit per Unit: $292
* Top Brand by Profit: Apple
* Top Distributor by Profit: Tottus

#### Key Insights

* Profit peaks in September ($2.51M) and dips in November.
* Positive correlation exists between unit cost and selling price.
* Huawei has the highest profit margin (61%) despite low volume.
* Samsung operates at the lowest margin (28%).
* Operator margins are relatively tight (35–37% range).
* Profit performance is uneven across distributors.

#### Strategic Implication

Pricing strategy appears effective overall, but margin optimization opportunities exist across selected brands

## 📊 Dashboard 3

### Market Concentration & Operational Performance — Where Is Performance Concentrated?
<img width="8192" height="5121" alt="salesphone3" src="https://github.com/user-attachments/assets/ec62d541-1e82-4c4f-8d1d-873f66901c73" />

#### KPIs

* Top Revenue Brand: Apple
* Top Volume Brand: LG
* Top Profit Brand: Apple
* Top 3 Brand Revenue Share: 70%
* Top Distributor by Units: Tottus

#### Key Insights

* Top 3 brands control 70% of total revenue — indicating high concentration risk.
* Apple alone contributes 30% of total profit.
* LG drives volume but not highest profit.
* Revenue share by operator is concentrated (Tuenti at 33%).
* Thursday is the strongest sales day; Monday the weakest.
* Distributor dependency is significant.

#### Strategic Implication

The company is operationally efficient but structurally dependent on a small group of brands and distributors.

## 📌 Executive-Level Insights

1. The company operates at a strong overall margin of 36%.
2. Growth trajectory is positive post-2020 recovery.
3. Revenue and profit concentration creates strategic vulnerability.
4. Distributor and operator performance materially influence results.
5. Seasonal and weekday patterns present optimization opportunities.
6. Some high-margin brands are under-leveraged in volume.

## 🚀 Strategic Recommendations

1. Diversify brand portfolio to reduce 70% concentration dependency.
2. Expand marketing for high-margin but low-volume brands.
3. Strengthen strategic partnerships with top distributors.
4. Develop Q4-specific campaigns to reduce seasonal dips.
5. Optimize pricing strategy for low-margin brands.
6. Explore geographic expansion in high-performing countries.

## 🛠 Technical Skills Demonstrated

* Advanced Excel Dashboard Design
* Power Pivot Data Modeling
* Relationship-Based Data Model
* Time Intelligence Calculations
* Profitability Analysis
* Contribution & Concentration Analysis
* KPI Engineering
* Executive Data Storytelling

## 📌 Conclusion

This project demonstrates the ability to move beyond basic reporting into strategic analytics by connecting growth performance, 
profitability structure, and market concentration risk into a cohesive executive narrative.

The dashboards provide actionable insights that support pricing decisions, distribution optimization, risk mitigation, and market 
expansion strategies.



