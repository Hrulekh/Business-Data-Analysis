# Business-Data-Analysis

In this project, I will be analyzing one year of Bhama’s sales and billing data to tackle three 
key challenges that are crucial to its operations. First, I aim to identify how effective different 
promotional products are in driving sales understanding what works and what doesn’t in 
Bhama’s current marketing mix. Second, I’ll be organizing and analyzing sales data based on 
HSN codes, which is essential for ensuring GST compliance and avoiding costly penalties. 
Finally, I’ll explore performance trends across different times of the day, days of the week, 
and months of the year to understand when the store sees peaks and slumps in activity. 

--Results and Findings--

1.Promotion Effectiveness (Problem 1)

Average Sales: ‘No Promotion’ and ‘Festival Sale’ show highest average sales values.
Profit Margin: ‘No Promotion’ has the highest margin (~40%), whereas ‘Clearance Sale’ shows negative margins (losses).
Regression: R² ≈ 0.02 (low) — simple model using only discount and promo type explains little variance in sales, implying other factors (seasonality, product mix, location) matter.
Preliminary insight: Targeted, moderate promotions (festival/seasonal) are more effective than steep blanket discounts. Clearance should be used carefully.

2.HSN Code Analysis (Problem 2)

Top HSNs by Revenue: 91021100, 71131100, 42022290 lead in total sales.
GST anomalies: None detected in the synthetic dataset (GST values in expected range).
Preliminary insight: Focus inventory and marketing on the high-revenue HSNs; consider promotions to boost underperforming HSN categories where margin allows.

3.Time-based Performance (Problem 3)

Daily trend: Sales are spiky and event-driven; no steady linear growth in the period.
Monthly trend: Highest revenue months include April, March and May; slower months include September and December.
Preliminary insight: Allocate staff and stock for March–May peaks; use low months for restocking, training, or targeted offers.

4.Clustering (Unsupervised ML)

K-Means (k=3) separated transactions into low, medium, and high performance groups, showing that high sales often occur with low-to-moderate discounts, while large discounts are often associated with low revenue.
