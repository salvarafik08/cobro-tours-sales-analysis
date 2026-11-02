# cobro-tours-sales-analysis
Cobro Tours and Travel – October 2026 Sales Analysis

A sales analysis and interactive dashboard for Cobro Tours and Travel, covering October 2026 bookings (all amounts in AED).

Note: Company, supplier and client names have been anonymized. Suppliers appear as SUPPLIER 01…, clients as CLIENT 01….

File	Description :

Cobro_Tours_and_Travel_October_Sales_Analysis.xlsx	
Excel workbook with the cleaned booking data and formula-driven summary sheets
Cobro_Tours_and_Travel_Dashboard.twbx	Tableau packaged workbook (data included)

Excel sheets :
Summary – total sales, cost, profit, margin, bookings, profit by category
Data – 599 bookings (date, category, supplier, client, detail, cost, sale, profit)
Visa_Types – profitability by visa product
Suppliers – bookings, sales and profit per supplier
Daily – daily trend, cumulative profit and weekday analysis

Tableau views :
Daily trend, daily profit and running total, profit by category, supplier scatter, visa supplier share, weekday heatmap, zero-profit bookings, and visa types.

Key metrics (October 2026):
Total sales: AED 550,534
Total profit: AED 69,273 (12.6% margin)
Bookings: 599
Visa accounts for about 65% of total profit

Key findings :
  - Visa drives the business. Visa made AED 45,184 of the AED 69,273 total profit (65%) from 395 of 599 bookings.
  -Ticketing is a weak earner. Tickets brought in AED 142,137 in sales (26% of the total) but only a 9.4% margin, below the 12.6% company average.
  -"Others" barely pays. 52 bookings earned just AED 753 profit, a 4.4% margin.
  -High margin, tiny volume. Dummy tickets have a 68% margin but only AED 1,696 in total profit.
  -Supplier concentration risk. One supplier (Supplier 23) provides 188 of 395 visa bookings and 59% of visa profit.
  -Not every visa product pays equally. Profit per visa is about AED 153 for 60-day A2A, AED 96 for 60-day Dubai and only AED 55 for 30-day Dubai.
  -Zero-profit bookings. 43 bookings (7% of the total) made no profit, worth AED 17,098 in sales. 30 of them are in "Others".
  -Sundays are slow. Only 9 bookings and AED 457 profit, against AED 10,000 to 14,000 on Monday to Friday. The best single day was 14 October (AED 5,628).

Recommendations :
  -Review pricing on 30-day Dubai visas and tickets. These are high-volume, low-margin lines, so a small price rise would add profit.
  -Investigate the zero-profit bookings. Check whether they are refunds, voids or pricing mistakes, and set a minimum margin for "Others".
  -Reduce reliance on one visa supplier. Move some volume to other suppliers such as Supplier 02 (20% margin) and Supplier 25 (22% margin).
  -Promote the better visa products. Extensions and 60-day B2B visas earn around AED 170 to 180 per booking.
  -Look at weekend demand. Test a Sunday offer or confirm that the office is simply closed.

Data cleaning steps :
  -Trimmed extra spaces and converted names to uppercase.
  -Standardized supplier and client names (spelling variants were kept separate in this version).
  -Checked each profit figure against sale minus cost (Profit_Check column).
  -Anonymized company, supplier and client names for sharing.

How to use :
  -Open the .twbx file in Tableau Desktop or Tableau Public.
  -Or open the .xlsx file in Excel to explore the data and formulas.

Tools :
  -Microsoft Excel 
  -Tableau
