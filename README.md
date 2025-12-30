# 🍽️ Zomato Bangalore Restaurant EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Zomato Bangalore restaurant dataset** to uncover insights related to restaurant locations, cuisines, ratings, pricing, and customer preferences.  
The goal is to understand food trends in Bangalore and support **data-driven decision making** in the restaurant industry.

The analysis is implemented in a Jupyter Notebook using Python and popular data analysis libraries.

---

## 🎯 Objectives
- Identify locations with the highest number of restaurants  
- Analyze the **Top 10 most popular cuisines** in Bangalore  
- Compare **Online Orders vs Table Booking** trends  
- Study **rating distribution across different cost categories**  
- Detect restaurants with **high votes but low ratings**  
- Locate **top low-cost, high-rated restaurants** using map-based analysis  

---

## 📂 Dataset Information
- **Source:** Zomato Bangalore Restaurants Dataset  
- **Records:** Restaurants listed in Bangalore  

### Key Columns
- `name` – Restaurant name  
- `location` – Area in Bangalore  
- `cuisines` – Types of cuisines served  
- `rate` – Restaurant rating  
- `votes` – Number of user votes  
- `approx_cost(for two people)` – Average cost for two  
- `online_order` – Online ordering availability  
- `book_table` – Table booking availability  
- `rest_type` – Type of restaurant  

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Jupyter Notebook**

### Libraries
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **Folium** – Map-based visualization  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Import dataset
- Inspect structure and data types

### 2️⃣ Data Cleaning
- Handle missing values  
- Convert rating and cost columns to numeric format  
- Remove duplicates and irrelevant columns  

### 3️⃣ Exploratory Data Analysis (EDA)
- Location-wise restaurant distribution  
- Top 10 cuisines analysis  
- Online orders vs table booking comparison  
- Rating distribution by cost category  
- High votes but low ratings analysis  
- Low-cost, high-rated restaurants identification  

### 4️⃣ Data Visualization
- Bar charts for location and cuisine distribution  
- Pie chart for online orders vs table bookings  
- Box plots for rating vs cost categories  
- Scatter plot for votes vs ratings  
- **Geographical map visualization using Folium**

---

## 📊 Key Insights

### 1️⃣ Which Location Has the Most Restaurants
<img width="1000" height="500" alt="Top 10 locations" src="https://github.com/user-attachments/assets/b2267849-dbd6-4299-a375-37f81249decf" />

**Insight:**  
BTM has the highest number of restaurants, followed by Koramangala 5th Block and HSR, indicating these areas are major food hubs driven by high demand and commercial activity.

---

### 2️⃣ Top 10 Most Popular Cuisines
<img width="1000" height="500" alt="Top 10 cuisines" src="https://github.com/user-attachments/assets/b20d536e-f4e0-4d39-bea1-42a9d6caff2d" />


**Insight:**  
North Indian cuisine dominates Bangalore’s restaurant landscape, followed by Chinese and South Indian cuisines, reflecting strong customer preference for familiar and comfort food options.

---

### 3️⃣ Online Orders vs Table Booking
<img width="960" height="480" alt="Online Vs Booking" src="https://github.com/user-attachments/assets/a66e3a14-4b28-434b-a11d-a69895cb35a3" />

**Insight:**  
More than **80% of restaurants support online orders**, highlighting a strong shift toward convenience-based dining and digital food delivery platforms.

---

### 4️⃣ Rating Distribution by Cost Category
<img width="640" height="480" alt="Rating Distribution" src="https://github.com/user-attachments/assets/26e84c9a-df27-4594-87f4-2f96d7991f74" />

**Insight:**  
Mid-range and premium restaurants generally receive higher and more consistent ratings, while budget restaurants show wider variation in customer satisfaction.

---

### 5️⃣ Restaurants with High Votes but Low Ratings
<img width="1000" height="600" alt="Restaurants" src="https://github.com/user-attachments/assets/06bdb131-af4f-4a50-b9a5-f0cdc514c65c" />

**Insight:**  
Some restaurants attract large customer volumes despite lower ratings, suggesting popularity driven by factors such as location, pricing, or brand visibility rather than food quality alone.

---

### 6️⃣ Top 10 Low-Cost, High-Rated Restaurants & Map Analysis
<img width="1130" height="493" alt="map" src="https://github.com/user-attachments/assets/0b3b0656-0833-4be7-9102-df07e2950613" />


**Insight:**  
Several affordable yet highly rated restaurants are concentrated in high-demand areas, proving that quality dining in Bangalore is not limited to expensive restaurants.

---

## ✅ Conclusion
This analysis highlights how **location, cuisine preference, pricing, and convenience** strongly influence restaurant success in Bangalore.  
The insights can help restaurant owners, food delivery platforms, and customers make informed decisions.

