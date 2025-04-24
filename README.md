# Revenue-Performance-Overview
![image](https://github.com/user-attachments/assets/af5ad4d1-b0a6-4b96-8f84-6fc02b6ed944)
# Business Revenue Dashboard Summary
This EXCEL dashboard provides a comprehensive overview of Worldwide PVT Ltd's revenue performance across multiple dimensions:

Total Revenue: ₹19.58 Cr, with ₹10.46 Cr from IGST (interstate), ₹4.71 Cr domestic, and ₹1.18 Cr classified as others.

Top Contributor: Star Union Dai Ichi Life Insurance with ₹11.93 Cr in revenue.

Quarter-wise Performance: Q4 leads with ₹6.48 Cr, marking a 235% increase over the previous quarter.

Monthly Peak: December shows the highest revenue at ₹3.75 Cr.

State-wise Leader: Maharashtra contributes ₹4.17 Cr, followed by Delhi and Telangana.

Tax Collection: Highest in Q4 at ₹2.73 Cr.

# clean process
Data Cleaning Steps
Split State & Company using LEFT, FIND, and RIGHT

Extract Month with MONTH(date)

Create Quarter using CHOOSE + MATCH for Indian fiscal year (starts in April)

Use VLOOKUP to fetch related info (state codes, tax rates, etc.)

Text cleaning with REPLACE, FIND, LEN as needed

# Visualizations
Bar Chart → Company-wise or State-wise revenue

Line Chart → Monthly revenue trend

Treemap → State-wise revenue distribution

Waterfall → Quarter-wise revenue or tax flow
