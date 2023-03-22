# OYO-Rooms---Sales-Insight-

Revenue insight is a process of analyzing and interpreting data to gain insights into revenue performance. In the case of OYO Rooms, revenue insight would involve analyzing data related to the company's revenue streams, such as bookings, occupancy rates, and pricing.

The goal of revenue insight for OYO Rooms would be to identify patterns and trends in the data that can be used to optimize revenue performance. For example, the analysis may reveal that certain types of rooms or locations are more popular among customers, which can inform pricing strategies and promotional activities.

### Task 

1. Data Pre-Processing
2. Define a key Metrics 
3. Data Modeling 
4. Creat Dashboard 
5. identify  Insight of trends and patterns  

### key Metrics 

1.Revenue	To get the total revenue_realized	Revenue = SUM(fact_bookings[revenue_realized])

2.Total Bookings	To get the total number of bookings happened	Total Bookings = COUNT(fact_bookings[booking_id])

3	Total Capacity	To get the total capacity of rooms present in hotels	Total Capacity = SUM(fact_aggregated_bookings[capacity])

4	Total Succesful Bookings	To get the total succesful bookings happened for all hotels	Total Succesful Bookings = SUM(fact_aggregated_bookings[successful_bookings])	

5	Occupancy %	"Occupancy means total successful bookings happened to the 
total rooms available(capacity)"	Occupancy % = DIVIDE([Total Succesful Bookings],[Total Capacity],0)	


Note: all 27 metrics and formulas are in excel file 
