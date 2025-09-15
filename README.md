# 🚖 Uber Ride Analysis

This project provides an in-depth **Exploratory Data Analysis (EDA)** of Uber ride bookings.  
Using **Python (Pandas, NumPy, Matplotlib, Seaborn)**, the dataset is cleaned, transformed, and visualized to uncover key insights about ride patterns, cancellations, customer/driver behavior, and vehicle preferences.

---

## 📂 Project Structure
├── ncr_ride_bookings.csv # Dataset
├── UBER Analysis.ipynb # Jupyter Notebook with full code
├── UBER Analysis.pdf # Exported analysis report
└── README.md # Project documentation


---

## 📊 Dataset Description

The dataset contains **150,000+ Uber ride bookings** with the following key columns:

- **date & time** → When the booking was made  
- **booking status** → Completed, Cancelled by Customer/Driver, Incomplete  
- **vehicle type** → Auto, Go Mini, Go Sedan, Bike, eBike, UberXL, Premier Sedan  
- **pickup & drop location** → Ride start and end points  
- **ride distance & booking value** → Distance traveled and fare  
- **driver & customer ratings** → 1-5 scale feedback  
- **payment method** → UPI, Cash, Card, Wallet  

---

## 🧹 Data Cleaning

- Filled missing values using mean/mode or placeholders (e.g., *Reason Unknown*).  
- Converted data types (`date`, `time`, categorical variables).  
- Added new features like **hour** and **timeZone** (Morning, Afternoon, Evening, Late Night).

---

## 🔎 Key Insights

### ⏰ Peak Demand Times
- **Afternoon (35.9%)** and **Morning (33.1%)** account for ~69% of rides.  
- Low demand in **Late Nights (6.4%)**.  
➡ Recommendation: Increase driver supply in peak slots and run promotions in off-peak hours.  

### 🚘 Vehicle Preferences
- **Autos (28.6%)** dominate bookings.  
- **Go Mini + Go Sedan = ~43%**, showing strong car preference.  
- **eBike (8.1%)** and **UberXL (3.4%)** have limited adoption.  

### 📍 Pickup Locations
- Identified **Top 5 & Bottom 5 pickup hubs**, useful for demand planning.  

### 📉 Booking Success Rate
- Overall success rate: **62.5%**  
- Driver cancellations: **18.1%**  
- Customer cancellations: **7.0%**  

### ⭐ Ratings
- Customers are highly satisfied (**4.40–4.41 across vehicles**).  
- Drivers rate slightly lower (**~4.23–4.24**).  
- Highest customer rating: **Go Sedan (4.41)**  
- Highest driver rating: **UberXL (4.24)**  

---

## 📊 Visualizations

Some of the visual insights include:
- 📈 **Bookings by time zones** (Pie Chart)  
- 🚗 **Most opted vehicle types** (Bar Chart)  
- 📍 **Top 5 pickup locations** (Horizontal Bar Chart)  
- 📉 **Cancellation trends** (Pie Chart with donut style)  
- ⭐ **Customer vs Driver Ratings** (Grouped Bar Chart)  

---

   git clone https://github.com/your-username/uber-analysis.git
   cd uber-analysis
