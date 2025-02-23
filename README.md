# FlightRevenueMaximizer

## Project Overview
**Flight Revenue Maximizer** is a data-driven project focused on analyzing airline occupancy rates and revenue streams to optimize profitability. Using an SQLite database and Python-based data analysis, the project identifies low-performing flights and offers insights to improve seat occupancy and boost the average profit per seat.

The goal is to help airlines enhance operational strategies, optimize pricing, and increase revenue while maintaining high customer satisfaction.

---

## Dataset
- **Source:** Airline’s internal SQLite database (Not directly available on GitHub due to size constraints).
- **Contents:**  
  - **Flights:** Flight details including schedules, routes, and occupancy rates.  
  - **Aircraft:** Data on aircraft models, seat capacities, and configurations.  
  - **Bookings:** Booking records, fare classes, and passenger information.

**The full SQLite database is too large to upload directly to GitHub. You can download it from the link below:**

[Download SQLite Database](https://drive.google.com/file/d/1YJxetrnY7wOaT2NGPMWNaju63CyAaDgm/view?usp=share_link)

---

## Tools and Technologies
- **Programming Language:** Python 3.x  
- **Data Analysis Libraries:** Pandas, NumPy, SQLite3  
- **Data Visualization:** Matplotlib, Seaborn  
- **Database:** SQLite  
- **IDE:** Jupyter Notebook  

---

## Key Features and Analysis

1. **Occupancy Rate Analysis:**  
   - Calculated occupancy rates across different flights and aircraft.  
   - Identified underperforming routes with low seat utilization.

2. **Revenue Insights:**  
   - Analyzed total revenue, average revenue per ticket, and fare class distribution.  
   - Compared revenue performance across different aircraft models.

3. **Pricing Strategy Evaluation:**  
   - Evaluated fare classes (Business, Economy, Comfort) and their impact on occupancy and revenue.  
   - Suggested dynamic pricing strategies to optimize seat utilization.

4. **Simulation of Increased Occupancy:**  
   - Modeled the financial impact of a 10% increase in seat occupancy.  
   - Highlighted potential revenue growth through optimized pricing and resource allocation.

---

## Future Enhancements

- Integrate real-time flight data for dynamic analysis.
- Develop an interactive dashboard (using Dash/Plotly) for better visualization.
- Implement machine learning models for demand forecasting and dynamic pricing.
