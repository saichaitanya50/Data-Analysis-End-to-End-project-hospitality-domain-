# Data-Analysis-End-to-End-project-hospitality-domain-


**Data Analysis End-to-End Project in the Hospitality Domain**

**Introduction:**
Welcome to my data analysis project focused on the hospitality domain. In this project, I have analyzed datasets related to hotels, room bookings, and other relevant information to gain insights into business performance over time. The project utilizes various data processing techniques, data wrangling, and Power BI for visualization and analysis.

**Tech Stack:**
- Power BI
- Data Processing
- Data Wrangling
- Power Query
- DAX (Data Analysis Expressions)

**Datasets Used:**
The project utilizes five CSV files:
1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings

**Description of Columns:**
- **dim_date:** Contains information about dates, including month, year, week number, and day type (Weekend or Weekday).
- **dim_hotels:** Provides details about hotels, including unique IDs, names, categories (Luxury or Business), and cities.
- **dim_rooms:** Describes different room types within hotels, including room IDs and classes (Standard, Elite, Premium, Presidential).
- **fact_aggregated_bookings:** Presents aggregated booking data, including hotel IDs, check-in dates, room categories, successful bookings, and capacities.
- **fact_bookings:** Contains detailed booking information, including booking IDs, hotel IDs, booking dates, check-in/check-out dates, number of guests, room categories, booking platforms, ratings given, booking status, and revenue-related metrics.

**Metrics Analyzed:**
1. Revenue WoW change %
2. Occupancy WoW change %
3. ADR WoW change %
4. RevPAR WoW change %
5. Realisation WoW change %
6. DSRN WoW change %

**Dashboard Insights:**
- Total Revenue: Sum of revenue realized from bookings.
- Total Bookings: Number of bookings made.
- Total Capacity: Sum of maximum room capacities across hotels.
- Total Successful Bookings: Number of successful room bookings.
- Occupancy %: Percentage of rooms successfully booked compared to total capacity.
- Average Rating: Average ratings given by customers.
- Total Cancelled Bookings: Number of bookings cancelled.
- Cancellation %: Percentage of bookings cancelled.
- Total Checked Out: Number of bookings successfully checked out.
- Total No Show Bookings: Number of bookings where customers did not show up.
- No Show Rate %: Percentage of bookings where customers did not show up.
- Booking % by Platform: Percentage contribution of each booking platform.
- Booking % by Room Class: Percentage contribution of each room class.
- ADR (Average Daily Rate): Average revenue generated per room sold.
- Realisation %: Percentage of successful bookings out of total bookings.
- RevPAR (Revenue Per Available Room): Revenue generated per available room.
- DBRN (Daily Booked Room Nights): Average number of rooms booked per day.
- DSRN (Daily Sellable Room Nights): Average number of rooms available for sale per day.
- DURN (Daily Utilized Room Nights): Average number of rooms successfully utilized per day.

**Weekly Change Metrics:**
- Revenue WoW change %: Percentage change in revenue week over week.
- Occupancy WoW change %: Percentage change in occupancy week over week.
- ADR WoW change %: Percentage change in Average Daily Rate week over week.
- RevPAR WoW change %: Percentage change in RevPAR week over week.
- Realisation WoW change %: Percentage change in Realisation week over week.
- DSRN WoW change %: Percentage change in DSRN week over week.

**Conclusion:**
This project provides valuable insights into the hospitality domain, helping businesses track performance metrics, analyze trends, and identify areas for improvement. By leveraging Power BI and various data analysis techniques, businesses can make informed decisions to enhance customer satisfaction and optimize revenue generation.

