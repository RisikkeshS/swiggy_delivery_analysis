
# Swiggy Delivery Performance Analysis

This is a complete end-to-end business analytics portfolio project using a simulated dataset modeled after Swiggy's delivery operations. The goal is to explore operational inefficiencies, delivery delays, cancellations, and customer experience patterns—and to propose data-driven recommendations for improvement.

## Objective

Analyze food delivery operations across different zones, time periods, partners, and restaurants to identify patterns in:
- Delivery delays
- Order cancellations
- Customer ratings
- Time-based and partner performance

## Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

## Key Steps

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

## Business Recommendations

1. The North zone had the highest cancellation rate—nearly double that of other zones. Swiggy should audit vendor reliability in this region and consider assigning buffer partners during peak times.

2. Delivery delays spike between 7–9 PM, especially on Fridays and Saturdays. Swiggy could dynamically allocate more delivery partners or reroute traffic during these high-load windows.

3. Certain delivery partners consistently show high average delays. A tier-based system should be introduced to reward top performers and retrain or replace the lowest-performing partners.

4. Customer ratings tend to dip on weekends, particularly on Saturdays. Weekend-specific quality checks for restaurants and optional pre-scheduled orders can help improve experience.

5. A few restaurant-zone combinations had both low ratings and high cancellation rates. Swiggy should flag these vendors for review or probation.

6. Weekend volume drives both delays and cancellations. A predictive staffing model should be used to pre-assign additional delivery capacity in hotspots every weekend.

## Dataset

The dataset was synthetically generated using Python to reflect realistic Swiggy-style operations and contains:
- Order times and delivery times
- Delivery delays (with some noise)
- Partner IDs, restaurant names, zones
- Ratings and cancellations
- Messy and inconsistent formats for cleaning practice

## How to Run

1. Clone the repository
2. Open the notebook: `Swiggy_Portfolio_Project_Python.ipynb`
3. Follow along the cleaning, feature engineering, EDA, visualization, and recommendations flow

## Notes

This project was created as part of a real-world business analyst portfolio to demonstrate applied data wrangling, KPI generation, visualization, and insight storytelling skills.
"# swiggy_delivery_analysis" 
"# swiggy_delivery_analysis" 
