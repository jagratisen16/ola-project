#  Ola Booking Data Analysis – Power BI Project

##  Overview
This Power BI project analyzes Ola ride booking data to uncover key insights related to booking performance, cancellations, customer and driver behavior, vehicle usage patterns, and payment preferences. The analysis helps stakeholders identify service bottlenecks and make data-driven decisions to improve operational efficiency.


##  Dataset

- **File Name:** `booking - Sheet1.csv`
- **Total Records:** 100
- **Columns:** 21 attributes including booking metadata, vehicle details, ratings, payment methods, and reasons for cancellations.

###  Key Fields:
- **Booking Info:** Booking ID, Date, Time, Booking Status
- **Ride Info:** Pickup & Drop Locations, Vehicle Type, Ride Distance, Booking Value
- **Ratings:** Customer and Driver Ratings
- **Cancellations:** Reasons for Customer and Driver cancellations
- **Payment:** Method of payment used (Cash, UPI, Wallet, etc.)

##  Objectives

- Evaluate overall booking performance and ride completion rates
- Identify top cancellation reasons from customers and drivers
- Assess customer and driver satisfaction via rating metrics
- Analyze trends in vehicle type usage
- Explore ride cost and distance patterns
- Examine popular locations and payment preferences

##  Key Insights

- **Success Rate:** 62% of bookings were completed successfully  
-  **Failures:** 38% were either canceled or incomplete  
  - 16% canceled by customer  
  - 12% incomplete  
  - 10% canceled by driver

-  **Top Customer Cancellation Reasons:**
  - Driver not moving toward pickup
  - AC not working
  - Change of plans

-  **Driver Cancellation Reasons:**
  - Customer-related issues
  - Personal/car issues

-  **Popular Vehicle Types:**  
  `eBike`, `Prime Sedan`, and `Auto` were most frequently booked

-  **Top Locations:**  
  **Pickup:** Bagalakunte, Koramangala, Whitefield  
  **Drop:** Banashankari, Bellandur, BTM 2nd Stage

-  **Ratings (out of 5):**
  - Avg Customer Rating: **4.14**
  - Avg Driver Rating: **4.25**

-  **Payment Method Usage:**
  - UPI, Wallet, and Cash are most preferred

   **Avg Booking Value:** ₹281.51  
  **Avg Ride Distance:** 12.33 km

## Tools & Technologies

- **Power BI Desktop** for interactive visualizations and dashboards
- **Microsoft Excel / CSV** for data input
- **DAX** for custom measures (e.g., Total Bookings, Avg Rating)

## Power BI Dashboard Features

- **KPIs:** Total Bookings, Success Rate, Avg Ratings, Revenue
- **Pie Charts:** Booking Status, Payment Methods
- **Bar Charts:** Cancellation Reasons, Vehicle Types
- **Line Graphs:** Rating Trends
- **Tables:** Detailed Booking Records
- **Filters/Slicers:** Date, Status, Vehicle Type, Payment Method

## Project Status

 Completed  
 Files included:
- `booking - Sheet1.csv` – Source data
- `ola project.pbix` – Power BI report

 ## License

This project is created for educational and analytical purposes. Feel free to use the insights and visuals with proper credit.

## Author

**[jagrati sen]**  



