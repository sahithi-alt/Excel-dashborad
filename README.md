# **Brewed Insights: Coffee Shop Sales Dashboard**

## Project Objective:
To gain a deeper understanding of customer purchasing behavior and optimize operations across three New York City coffee shop locations, transactional data from January to June 2023 was analyzed. This data was used to develop an interactive and dynamic dashboard that provides franchise owners with valuable insights into sales patterns, trends, and growth opportunities. The dashboard equips stakeholders with actionable information to make data-driven decisions for enhancing business performance and streamlining operations effectively.<br/>
Data Used:<br/> 
## **Key Performance Indicators (KPIs) for the Coffee Shop Sales Dashboard**

•	Total Revenue (daily, weekly, monthly).<br/>
•	Revenue by product category.<br/>
•	Revenue by product type (top 15 items).<br/>
•	Number of transactions per day.<br/>
•	Number of transactions by hour.<br/>
•	Transactions by product category and product type.<br/>
•	Peak sales hours (morning, afternoon, evening).<br/>
•	Sales trends by day of the week.<br/>
•	Monthly revenue trends.<br/>
•	Best-selling product categories and products.<br/>
•	Contribution of top-performing items to overall revenue.<br/>
•	Low-performing products or categories.<br/>
•	Preferred shopping days.<br/>
•	Preferred time slots for purchases.<br/>
•	Identification of low-sales periods.<br/>
•	Optimal times for staffing adjustments and inventory management.<br/>
•	Opportunities to optimize operating hours.<br/>
•	Revenue per transaction.<br/>
•	Revenue contribution by product type or category.<br/>

## **Process:**<br/>
* Added filters to the header row to quickly explore each field.<br/>
* Added a new column to calculate Revenue.<br/>
* Used MONTH and WEEKDAY functions to return numerical values.<br/>
* Added a new column to extract Hour from the transaction time.<br/>
* Inserted a PivotTable on a new tab to show revenue by month.<br/>
* In the field list, added Revenue to Values and Month to Rows.<br/>
* Added two more PivotTables to show the number of transactions by day of week and by hour of day.<br/>
* Used Count of transaction_id to calculate the number of transactions.<br/>
* Added a PivotTable  to show the number of transactions by product category, sorted descending by transactions.<br/>
* Used the Row Labels header to sort rows descending by Count of transaction_id.<br/>
* Addeed a PivotTable to show the number of transactions and revenue by product type, sorted descending and filtered to the Top 15 (by transactions.<br/>
* Added a "Top 10" value filter, and modify to show the top 15 items by Count of transaction_id.<br/>
* Added a slicer suggests data could be filtered by location. If specific locations are underperforming, targeted strategies (like local promotions) could be implemented.<br/>

## Business Insights:<br/>
### Astoria location:<br/>
**Adjust Operating Hours:**<br/>
•	Late evenings show minimal sales activity, suggesting an opportunity to shorten operating hours during unproductive periods. Focus on peak hours, especially between 7 AM and 10 AM, to enhance profitability.
**Targeted Promotions:**<br/>
•	Mondays exhibit a strong customer turnout. Weekday specials and discounts can capitalize on this trend.<br/>
•	Sundays witness lower footfall; introducing weekend-specific deals can drive customer traffic.<br/>
**Product Bundling:**<br/>
•	Popular items like Coffee and Bakery products can be bundled together to encourage higher average transaction values.<br/>
**Marketing Initiatives:**<br/>
•	Leverage tea’s position as the second-most popular category by promoting tea-based drinks.<br/>
•	Develop campaigns around top-performing products, such as Barista Espresso, to boost visibility and sales.<br/>
**Inventory Planning:**<br/>
•	Optimize inventory for high-demand products to avoid stockouts. Simultaneously, reduce overstock of underperforming items to improve cost efficiency.<br/>
**Strategic Opportunity:**<br/>
•	 Astoria experiences a strong sales spike during morning commute hours (7–10 AM) and a dip in evening activity (7–8 PM). Adjusting operating hours and focusing resources during peak times can help improve margins.<br/>
<img width="488" alt="Astoria location Dashboard" src="https://github.com/user-attachments/assets/73cef00e-e4e4-495e-9d4b-7a6108a0b832" />




## Hell’s Kitchen location <br/>
### Business Insights:<br/>
**Revenue Growth:<br/>**
•	Revenue showed consistent growth over six months, with a sharp increase from May to June ($52,599 to $56,957), likely driven by successful promotions or seasonal factors.<br/>
**Day-of-Week Transactions:<br/>**
•	Peak transactions occur midweek (Wednesday and Thursday), with Sunday seeing the lowest engagement. This trend suggests consumer activity is closely tied to workday routines.<br/>
**Hour-of-Day Transactions:<br/>**
•	The busiest period is between 7 AM and 11 AM, indicating a strong demand for breakfast and morning beverages. Afternoon and evening hours show lower activity, revealing opportunities to attract customers during off-peak hours.<br/>
**Product Performance:<br/>**
•	Coffee dominates sales with 20,187 transactions, followed by Tea (15,277) and Bakery (7,617). However, categories like Branded and Packaged Chocolate remain underwhelming.<br/>
•	High-performing products, such as Barista Espresso ($32,420), Brewed Chai Tea ($25,645), and Hot Chocolate ($23,586), are significant revenue drivers.<br/>
## **Recommendations:<br/>**
•	Introduce Sunday promotions to boost weekend engagement.<br/>
•	Expand on popular products (e.g., Coffee and Chai Tea) by offering seasonal flavors or variations.<br/>
•	Evaluate the inventory strategy for low-performing categories to reduce waste and improve efficiency.<br/>
•	Implement time-specific campaigns (e.g., breakfast combos) to maximize morning revenue.<br/>
•	Strategic Opportunity: Hell’s Kitchen benefits from consistent midweek performance and high morning sales. Targeted weekend promotions and leveraging popular products can further enhance profitability.<br/>
<img width="466" alt="Hells kitchen Dashboard" src="https://github.com/user-attachments/assets/f0f2dce8-2b31-49c5-af5b-0ec8ac6c8fb9" />



## Lower Manhattan location:<br/>
**Business Insights:<br/>**
**Revenue Trend:<br/>**
•	Revenue peaks in June at $54,446, showing steady growth from March onwards. This suggests effective strategies during the second quarter, possibly tied to promotions or seasonal demand.<br/>
**Transactions by Day of Week:<br/>**
•	Mondays lead in transactions, while weekends (Saturdays and Sundays) lag. This highlights a weekday-driven customer base.<br/>
**Transactions by Hour of Day:<br/>**
•	Peak hours are 7 AM to 11 AM, reinforcing the significance of breakfast and morning beverages in this location.<br/>
**Product Insights:<br/>**
•	Coffee is the most popular category, with 18,204 transactions, followed by Tea (13,912). Low-performing categories include Packaged Chocolate and Branded Items, which may require reassessment of inventory or marketing.<br/>
**Top Products:<br/>**
•	Barista Espresso leads in sales and revenue (5,320 transactions; $31,051), with other popular items including Brewed Chai Tea and Gourmet Brewed Coffee.<br/>
## **•	Recommendations:<br/>**
•	Launch targeted weekend promotions to address lower sales on Saturdays and Sundays.<br/>
•	Introduce new coffee flavors or variants to capitalize on its popularity.<br/>
•	Explore bundling high-performing items with less popular products to boost overall sales.<br/>
•	Strategic Opportunity: Lower Manhattan thrives on morning sales and weekday transactions. Strengthening weekend strategies and introducing innovative product offerings can help sustain growth.<br/>
<img width="461" alt="Lower Manhattan Dashboard" src="https://github.com/user-attachments/assets/4a203950-1da5-4881-9dde-c39194fc04ca" />


## **Final Conclusion:**<br/>
### **Across all locations:**<br/>
•	Peak Hours: Focus on the morning rush (7–10 AM) for maximum profitability.<br/>
•	Day-of-Week Strategy: Enhance weekend performance through targeted promotions and campaigns.<br/>
•	Product Optimization: Coffee and Tea are universal favorites, providing opportunities for innovation and bundling.<br/>
•	Inventory Management: Address underperforming categories to minimize waste while maintaining sufficient stock for high-demand items.<br/>
![image](https://github.com/user-attachments/assets/a96bc1c1-ea4d-4ba5-80c3-3afd36b2490f)


 
