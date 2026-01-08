#Sales analysis and forecasting  
Background 

-Large Uk retail chains operate across regions and manage inventory efficiently, and sales performance can fluctuate due to seasonal shopping periods and macroeconomic conditions such as inflation and unemployment. 

Business Problem 
-Differences in sale performance during holiday and non-holiday periods  
-Whether macroeconomic indicators influence sales trend 
-How historical sales patterns can inform forward-looking demand planning  

Objectives  
-Analyze overall sales trend across stores and trend 
-Assess the impact of holiday periods on sales performance 
-Examine the relationship between economic conditions and retail demand 
-Forecast future sales to support inventory optimization and high-level planning 

Key Insights 

In excel, 
-Overall Sales Performance 
-Non-holiday generates higher total sales than holiday period due to a greater number of non-holiday weeks. 
-Holiday periods show short-term spikes particularly in November and December, but their overall remains limited. 
-Outside of holiday periods, April records the highest sales level  

Key takeaway 

-While holiday periods drive short-term demand surges, most revenue is generated during regular trading periods. Inventory planning should therefore prioritize non-holiday demand stability while flexible for holiday spikes.  

Fuel Price and Sales 

-Fuel price is generally higher during non-holiday periods  
-No clear relationship observed between fuel price and sales. 

Key takeaway 
-Fuel price changes do not appear to influence retail demand at the aggregate level. 

CPI, Unemployment and sales  

-CPI remains stable throughout the period analysed and unemployment rates do not show a significant impact of weekly sales. 
-Sales fluctuate independently of the CPI and Unemployment movement.  

Key takeaway  
-As the large retailer is a necessity-based business, where demand is inelastic and less sensitive to macroeconomic factors, but this can capture broader economic context without overemphasizing short-term volatility. 

In Python, 
Overview 
-Dependent variable: Weekly Sales 
Independent variables: 
-Fuel Price 
-CPI 
-Unemployment 
-Temperature 

Key Takeaway 

Regression analysis confirms that short-term retail sales are weakly influenced by temperature, fuel prices, and CPI, while unemployment shows a modest long-term association with demand. Holiday periods provide temporary sales uplift but do not significantly alter overall demand trends. These results support the view that large retailers operate with relatively inelastic, necessity-driven demand. 

In Power BI, 

Page 1: Sales Overview 

Visuals: 
-Line chart: Total weekly/yearly sales 
-Card visuals: Total Sales, Average Weekly Sales 
This page presents an overview of total sales over time. Sales fluctuate throughout the year, reflecting seasonal and periodic demand variations. Peaks are observed in November, and December, highlighting both non-holiday and holiday-driven demand. This insight provides a foundation for understanding overall performance and planning inventory accordingly. 

Page 2 and 3: Holiday vs Non-Holiday Analysis 
-Card visuals: Total sales for Holiday vs non-Holiday 
-Line or Bar chart: Sales split by Holiday_Flag 
-Holiday periods generate short-term spikes in sales, particularly during November and December. However, non-holiday weeks contribute more to annual revenue due to higher frequency. This analysis demonstrates that while holiday sales are important for short-term stock planning, non-holiday weeks drive most overall demand, guiding inventory optimization strategies 

Page 4: External Factors Analysis 

Visuals: 
-Scatter charts: 
-Sales vs Fuel Price 
-Sales vs CPI 
-Sales vs Unemployment 
This page explores the impact of macroeconomic indicators on sales. Fuel price and CPI show minimal short-term influence on weekly sales, indicating that these variables do not significantly alter consumer demand. Unemployment exhibits a slow-moving effect, affecting sales trends over longer periods. These findings highlight the inelastic nature of demand for necessity-based retail, reinforcing the need to focus on internal operational and seasonal factors when planning inventory. 

Page 5: Sales Forecasting 
Visuals: 
-Line chart with forecasted sales for the next 12 months 
-Forecast line with confidence interval shading 
The forecasting chart projects future sales based on historical trends. Predicted peaks align with recurring holiday periods, while dips occur during typical non-holiday months. This forward-looking view supports strategic inventory planning, enabling the retailer to anticipate demand fluctuations and optimize stock levels. Although seasonality within the year cannot be fully captured due to yearly aggregation, the forecast provides reliable guidance for long-term trend planning 

Suggestions and recommendations  
-Prioritize Non-Holiday Inventory Stability 
-Non-holiday weeks account for most annual sales despite lower weekly peaks,so,Maintaining consistent baseline inventory levels throughout non-holiday periods to avoid frequent stockouts, as these weeks drive overall revenue performance. 
-Use Targeted Stock Uplift for Holiday Periods 
-Holiday weeks show clear short-term sales spikes, particularly toward the end of the year. Apply short-term inventory uplifts around major holiday periods rather than long-term stock increases, reducing overstock risk once demand normalizes. 
-Avoid Overreacting to Short-Term Economic Fluctuations 
-Fuel price and CPI changes do not meaningfully impact short-term sales performance. So, Inventory and replenishment decisions should not be frequently adjusted in response to short-term macroeconomic changes, allowing planners to focus on demand-driven signals. 
-Apply Trend-Based Forecasting for Inventory Planning 
-Forecasting highlights stable demand with recurring seasonal peaks. 
Use trend-based forecasts to guide high-level inventory allocation and supplier negotiations, while allowing operational teams to adjust tactically based on short-term demand signals. 

---

## 📈 Skills Demonstrated
- Data cleaning & aggregation
- Business-oriented analysis
- Excel pivot tables
- Power BI dashboards
- Insight storytelling
