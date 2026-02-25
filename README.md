Project Scope : 
Analyzed the full organ referral-to-transplant pipeline across multiple Organ Procurement Organizations (OPOs) — covering patient referrals, authorization decisions, procurement outcomes, and organ utilization (heart, liver, kidneys, lungs, pancreas, intestine).

 How It Was Achieved : 

Data Cleaning — Standardized inconsistent OPO data entry using CASE WHEN, validated referential integrity via LEFT JOIN gap analysis.
Window Functions — ROW_NUMBER, LAG, RANK for referral timelines and year-over-year procurement trends.
CTEs — Multi-level CTEs to break complex pipeline logic into clean steps.
JOINs — Combined patient demographics, referral records, death info, and organ outcomes across multiple tables.
Stored Procedures — Reusable summary reporting across OPOs


 Insights : 

Significant authorization gap between approached and authorized patients across OPOs
Kidney had the highest procurement rate, intestine and pancreas the lowest
Brain death referrals showed significantly higher authorization rates
Donation patterns varied by blood type, age, and race
Mechanism of injury was a strong predictor of organ viability


Impact : 

Identified authorization bottlenecks to improve OPO outreach strategies
Highlighted underserved donor demographics for targeted intervention
Delivered reusable SQL framework for ongoing procurement efficiency analysis

