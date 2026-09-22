# Shopping-Sales-Overview-What-a-Tableau-Dashboard-About-Customer-Behavior
The primary objective is to analyze a consumer shopping dataset to understand how revenue is generated across product category, size, gender, shipping type, season, and location, and to identify where the business's revenue is concentrated versus spread thin.


Problem Being Addressed
The analysis seeks to answer:
· Which product categories, sizes, and customer segments are driving the most revenue, and how concentrated is that revenue?
· How does shipping type, season, and location affect purchase volume, and do the biggest-name markets actually lead in sales?

Datasets and Methodologies
Dataset: The analysis uses a consumer shopping dataset containing independent variables (Category, Size, Gender, Shipping Type, Season, Location) and dependent variables (Average Purchase Amount, Total Revenue).
Methodologies: The primary methodology involved building an interactive Tableau dashboard with filters for size and category, breaking down average purchase by category, size, gender, shipping type, season, and top locations.

Industry Type
Retail / e-commerce, with revenue concentration and purchase incentives as the primary measures of business health.

Data Story
The data tells a story around where a retail business's revenue actually comes from. It highlights average purchase by category, size, and gender, the shipping types driving the most orders, seasonal spending patterns, and which locations lead in sales.

Stakeholders of Project
Merchandising, marketing, and inventory planning teams.


What Success Means to the Industry
Protecting the categories and sizes that already drive the bulk of revenue.
Understanding which purchase incentives (like shipping) actually convert, even when they cost more to fulfill.
Not over-indexing on assumed "big" markets when smaller ones may be performing just as well.


Pre-Analysis
Project Split
Category One: Independent Variables
· Category
· Size
· Gender
· Shipping Type
· Season
· Location


Category Two: Dependent Variables
· Average Purchase Amount
· Total Revenue


Potential Analysis/Questions
Average purchase performance by category
Average purchase performance by size
Average purchase performance by gender
Order volume performance by shipping type
Revenue performance by season
Revenue performance by location
Identification of the top 5 best-selling items
Identification of revenue concentration risk across categories and sizes

Potential Insights
Finetune inventory priority around the sizes and categories that drive the most revenue, to avoid stockouts in high-impact areas.
Finetune shipping strategy if a costlier shipping option is shown to drive more volume than cheaper ones.
Finetune seasonal planning around the peak season identified in the data.
Finetune regional marketing spend if traditional "hub" states aren't actually leading in sales.

In Analysis
Average Purchase by Category
Observations:
· Clothing topped the chart, generating $104,264.00 in average purchase value.
· Accessories ranked second, at $74,200.00.
· Footwear ranked third, at $36,093.00.
· Outerwear was the lowest, at $18,524.00.

Pre Insight:
· Clothing and Accessories together account for over 76% of total sales, making these two categories the core of the business model.
· Footwear and Outerwear lag well behind, suggesting either lower demand or an opportunity for growth if properly marketed.

Average Purchase by Size
Observations:
· Size M led at $105,167.00.
· Size L followed at $61,667.00.
· Size S recorded $40,468.00.
· Size XL was the lowest, at $25,779.00.

Pre Insight:
· M and L together represent the clear majority of purchase value, meaning they must be the top inventory priority at all times.
· Running out of stock in size M alone would instantly remove nearly half of the potential revenue, leading to significant lost sales.

Average Purchase by Gender
Observations:
· Male customers accounted for $157,890.00, roughly 67.7% of total sales.
· Female customers accounted for $75,191.00.

Pre Insight:
· The male segment is the primary revenue driver for the business by a wide margin, making it the segment most worth protecting and understanding further.
· The female segment, while smaller, still represents nearly a third of revenue and shouldn't be deprioritized entirely.

Average Order by Shipping Type
Observations:
· Free Shipping generated the single largest volume of orders among all shipping types (Free Shipping, Express, Store Pickup, Standard, 2-Day Shipping, Next Day).
· This holds despite Free Shipping likely being the most costly option for the business to fulfill.

Pre Insight:
· Free shipping functions as a significant purchase incentive rather than a pure cost center, since it generates the highest volume of sales of any option offered.
· The cost of offering free shipping should be weighed against its role in driving conversion, not evaluated as a stand-alone expense.

Seasonal Trend Report
Observations:
· Fall led the year at $60,018.00.
· Spring followed at $58,679.00.
· Winter recorded $58,607.00.
· Summer was the lowest, at $55,777.00.

Pre Insight:
· The peak in Fall suggests either preparation for holiday shopping or high demand for seasonal items during the transition out of summer.
· Spring and Winter are nearly tied, suggesting demand is fairly stable outside of the Fall peak and the Summer dip.
Top 10 Location
Observations:
· Montana led all locations at $5,784.00.
· California followed at $5,587.00.
· New York recorded $5,257.00.
· West Virginia recorded $5,174.00.
· Illinois, Idaho, Nevada, Alabama, and North Dakota also placed in the top 10.
Pre Insight:
· Major retail hubs like New York and California are present in the top 10 but do not lead the chart, suggesting either high competition in those states or that their sales volume is spread out among a larger population of non-top-10 states.
· Montana leading the list is notable given it isn't a traditional retail hub, suggesting an underlying regional demand pattern worth investigating further.

Data Visualization — Dashboard
<img width="2509" height="1057" alt="Screenshot (214)" src="https://github.com/user-attachments/assets/6ced90cb-9581-4deb-a1a0-5b7761237da4" />


The Shopping Sales Overview dashboard (filterable by size and category) brings the analysis together:
· Average Purchase by Category (bar) — Clothing ($104,264.00), Accessories ($74,200.00), Footwear ($36,093.00), Outerwear ($18,524.00).
· Average Purchase by Size (bar) — M ($105,167.00), L ($61,667.00), S ($40,468.00), XL ($25,779.00).
· Average Purchase by Gender (pie) — Male ($157,890.00, ~67.7%), Female ($75,191.00).
· Top 5 Items — a mixed-category showcase, confirming the business isn't reliant on a single product type within its best performers.
· Average Order by Shipping Type — Free Shipping leads order volume, ahead of Express, Store Pickup, Standard, 2-Day, and Next Day.
· Seasonal Trend Report — Fall ($60,018.00), Spring ($58,679.00), Winter ($58,607.00), Summer ($55,777.00).
· Top 10 Location (bar) — led by Montana ($5,784.00), California ($5,587.00), New York ($5,257.00), West Virginia ($5,174.00), and six other states.

General Observations
· Revenue is heavily concentrated rather than evenly spread — Clothing and Accessories account for over 76% of total sales, and size M alone represents nearly half of size-based revenue.

· The business's top-performing shipping option is also its costliest to fulfill, meaning the highest-volume driver and the highest-cost line item are the same thing — a dynamic worth watching closely.

· Gender revenue is lopsided (67.7% male) but not exclusive, and the female segment still represents a meaningful chunk of total sales.

· Geography doesn't follow population or "hub" assumptions — smaller states like Montana outperform California and New York, the two most commonly assumed retail powerhouses.

· Seasonality is present but mild — Fall leads, but Spring and Winter trail closely behind, with only Summer showing a clearer dip.

General Recommendations / Insights
· Treat size M and size L, and the Clothing and Accessories categories, as non-negotiable inventory priorities, since stockouts here carry outsized revenue risk.

· Keep free shipping as a core offer, treating its cost as a conversion investment rather than pure overhead, given it drives the highest order volume of any shipping type.

· Investigate why traditional hub states underperform relative to smaller states like Montana — this may point to competitive saturation in big markets or an underserved opportunity in smaller ones.

· Build inventory and marketing plans around the Fall peak, while treating Spring and Winter as steady secondary periods rather than off-peak.
· Continue supporting the female customer segment and Footwear/Outerwear categories, even though they trail the top performers, since they still contribute meaningfully to total revenue.

Data Limitations or Biases

· The dataset reflects a single reporting period, so it isn't possible to confirm whether the Fall peak and shipping-type patterns are recurring or specific to this period without a prior-period baseline.

· Average purchase figures are shown at the category, size, and gender level, but it isn't clear whether these are affected by differing customer counts per group — a segment with fewer, higher-spending customers could look similar to one with many moderate spenders.

· "Top 5 Items" is shown visually without exact revenue figures per item, so it isn't possible to quantify exactly how much each top item contributes relative to the others.

Future Research
· Bring in prior-period data to confirm whether the Fall seasonal peak and the free-shipping order-volume lead are stable patterns or specific to this snapshot.

· Layer in customer count data alongside average purchase value, so category and size performance can be assessed by both volume and value rather than average alone.

· Investigate the underlying drivers behind Montana and other non-hub states outperforming larger markets — this could inform regional expansion or marketing strategy.

· Analyze the cost of free shipping directly against the additional order volume it generates, to quantify whether it's net-positive for the business.

Analytical Tools
· Tableau — for interactive filtering by size and category, and the final dashboard (bar charts, a pie chart, a shipping-type breakdown, and a seasonal trend grid).

Conclusion
This analysis shows that the business's revenue is real but narrowly concentrated — in two product categories, two sizes, one dominant gender segment, and one shipping type that happens to be its costliest to fulfill. That concentration is both a strength and a risk: performance today depends heavily on a few categories, sizes, and incentives holding steady. The recommendations above focus on protecting what's already working (prioritizing M/L inventory, keeping free shipping, doubling down on Fall) while investigating the parts of the story that don't fit assumptions — particularly why smaller states are outperforming traditional retail hubs. Done together, these should help the business plan around what the data actually shows, rather than what conventional retail wisdom would suggest.
