
Swiggy Delivery Performance Analysis:

This is a complete end-to-end business analytics portfolio project using a simulated dataset modeled after Swiggy's delivery operations. The goal is to explore operational inefficiencies, delivery delays, cancellations, and customer experience patterns—and to propose data-driven recommendations for improvement.

Objective:

Analyze food delivery operations across different zones, time periods, partners, and restaurants to identify patterns in:
- Delivery delays
- Order cancellations
- Customer ratings
- Time-based and partner performance

Tools Used:

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

Key Steps

- Cleaned and transformed 2200+ rows of messy operational data
- Engineered new features like hour of day, day of week, is_weekend, delivery duration
- Derived KPIs such as:
  - Average Delivery Duration
  - % of Orders Delayed
  - Cancellation Rate
  - Zone-wise and Partner-wise Delivery Metrics
  - Restaurant-wise Rating Analysis
- Built multiple visualizations to explore and communicate trends
- Generated actionable business recommendations from real patterns

Business Recommendations:

1. ##Central Zone is Driving High Cancellations
The Central zone has nearly double the cancellation rate compared to other zones. This points to potential reliability issues, either from vendors or delivery partner availability.

Recommendation:
Swiggy should audit vendors in this zone for order acceptance and readiness behavior. Additionally, having backup delivery partners on standby during peak hours can help prevent last-minute cancellations.

2. ##Delivery Delays Peak at Specific Times
Delays are noticeably higher at 9 AM (especially on Sundays) and 7 PM on Fridays. These are likely high-order periods that aren't being matched with adequate delivery capacity.

Recommendation:
Introduce time-based dynamic fleet allocation. More delivery partners should be auto-assigned during these windows. Alternatively, traffic rerouting or smart batching logic can help absorb the pressure.

3. ##Customer Ratings Drop on Weekends
Ratings are consistently lower on weekends, with Saturday being the most affected. This suggests that order experience — food or delivery — is not being managed well during weekends.

Recommendation:
Introduce weekend-specific quality checks for restaurants. Swiggy can also allow pre-scheduled orders during peak hours to spread out the load. This gives kitchens more prep time and reduces stress on partners.

4. ##Some Restaurant–Zone Pairs Are Risky
A few restaurant and zone combinations have both high cancellation rates and low customer ratings — this is a clear red flag.

Recommendation:
These combinations should be flagged for internal review. Swiggy should engage with those vendors directly, consider applying probation rules, or deprioritize them temporarily in the app.

5. ##Midweek and Weekend Operational Bottlenecks
Wednesdays, Fridays, and Saturdays show clear signs of strain — more orders, more cancellations, and lower ratings.

Recommendation:
A predictive staffing model can help. Based on historical trends, Swiggy should pre-assign additional delivery capacity for those days and proactively limit restaurant exposure in overloaded zones if needed.

6. ##Consistently Poor Performer Partners
Some delivery partners have significantly higher average delays regardless of zone or time. These outliers affect the overall service reliability.

Recommendation:
A performance tiering system can help here. Top performers can be incentivized or prioritized for time-sensitive orders, while consistent low performers should be retrained or rotated out of priority slots.


Dataset:

The dataset was synthetically generated using Python to reflect realistic Swiggy-style operations and contains:
- Order times and delivery times
- Delivery delays (with some noise)
- Partner IDs, restaurant names, zones
- Ratings and cancellations
- Messy and inconsistent formats for cleaning practice

How to Run:

1. Clone the repository
2. Open the notebook: `Swiggy_Portfolio_Project_Python.ipynb`
3. Follow along the cleaning, feature engineering, EDA, visualization, and recommendations flow

Notes:

This project was created as part of a real-world business analyst portfolio to demonstrate applied data wrangling, KPI generation, visualization, and insight storytelling skills.
"# swiggy_delivery_analysis" 
"# swiggy_delivery_analysis" 
