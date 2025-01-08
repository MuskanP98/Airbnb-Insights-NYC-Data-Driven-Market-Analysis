### **APPLIED DATA SCIENCE ASSIGNMENT 02**  
**Muskan Patel**  

---

#### **Part I: Exploratory Analytics and Visualization of Data via Information Dashboard**

---

**Domain:**  
The domain selected for this assignment is **Airbnb rental listings in New York City (2011–2019)**. The dataset contains detailed information on Airbnb rental listings, including host details, location, pricing, and property features.  

---

**Data Source:**  
The dataset used is the **New York City Airbnb Open Data** from Kaggle. It comprises 49,000 observations across 16 variables, collected directly from Airbnb and regularly updated.  
- Link to dataset: [NYC Airbnb Open Data](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)  

---

**Variables Used in Dataset:**  
1. **id**: Unique identifier for each rental listing  
2. **name**: Name of the Airbnb rental listing  
3. **host_id**: Unique identifier for the host  
4. **host_name**: Name of the host  
5. **neighbourhood_group**: Borough where the listing is located  
6. **neighbourhood**: Specific neighborhood of the listing  
7. **latitude**: Latitude of the listing location  
8. **longitude**: Longitude of the listing location  
9. **room_type**: Type of room (e.g., entire home/apartment, private room, shared room)  
10. **price**: Nightly price for the listing  
11. **minimum_nights**: Minimum booking duration in nights  
12. **number_of_reviews**: Number of reviews for the listing  
13. **date**: Date of the most recent review  
14. **reviews_per_month**: Average number of monthly reviews  
15. **host_listings_count**: Number of listings owned by the host  
16. **availability_365**: Number of days the listing is available in a year  

---

**Relationships Between Variables:**  
The variables are mostly independent, except for the following:  
- **Price** is influenced by **room_type**, **location**, and **availability_365**.  
- **reviews_per_month** and **date of last review** are dependent on **number_of_reviews**.  

---

**Key Questions to Explore:**  
1. What are the most common types of Airbnb rental listings in NYC?  
2. Which boroughs have the most Airbnb rental listings?  
3. What is the average price of a listing in NYC?  
4. How does availability change throughout the year?  
5. What factors significantly affect the price of a listing?  

---

### **Problem Statement**  
The Airbnb rental market in New York City is highly dynamic and competitive, presenting challenges for hosts, guests, and policymakers. This project aims to:  
- Analyze patterns, trends, and factors influencing Airbnb pricing and availability.  
- Provide actionable insights for hosts to optimize listings, guests to make informed booking decisions, and policymakers to regulate the market effectively.  

**Objectives:**  
1. **Hosts:** Optimize pricing and improve listing features to attract more bookings.  
2. **Guests:** Identify affordable and desirable neighborhoods for bookings.  
3. **Policymakers:** Monitor market trends and ensure fair competition.  

This project leverages a large dataset to identify seasonal fluctuations, popular neighborhoods, and host attributes influencing rental success. Insights gained can drive better decision-making across stakeholders.  

---

### **15 Information Dashboards**

**1. Dashboard Name: New York Overview**  
- **Target Audience:** General public  
- **Purpose:** Provide an overview of Airbnb rental trends in NYC.  
- **Information Presented:** Listings on map, average price, reviews, and availability across boroughs.  
- **Actionable Insights:** Hosts can adjust prices, and guests can select neighborhoods based on budget and availability.  

**2. Dashboard Name: Types of Listings**  
- **Target Audience:** Travelers and tourists  
- **Purpose:** Show the variety of listing types available in NYC.  
- **Actionable Insights:** Helps travelers understand accommodation options and plan budgets.  

**3. Dashboard Name: Price Distribution**  
- **Target Audience:** Hosts and potential renters  
- **Purpose:** Visualize nightly price distribution across boroughs and room types.  
- **Actionable Insights:** Hosts can compare prices and adjust strategies; guests can identify price ranges by area.  

**4. Dashboard Name: Reviews by Month**  
- **Target Audience:** Hosts  
- **Purpose:** Analyze seasonal review patterns.  
- **Actionable Insights:** Helps hosts identify peak periods and adjust pricing.  

**5. Dashboard Name: Price vs. Availability**  
- **Target Audience:** Hosts  
- **Purpose:** Examine how price correlates with availability.  
- **Actionable Insights:** Optimize pricing based on availability trends.  

**6. Dashboard Name: Popular Hosts**  
- **Target Audience:** Guests  
- **Purpose:** Highlight top hosts in NYC.  
- **Actionable Insights:** Guests can book with highly rated and reliable hosts.  

**7. Dashboard Name: Room Type by Neighbourhood**  
- **Target Audience:** Hosts and renters  
- **Purpose:** Analyze room type distribution across neighborhoods.  
- **Actionable Insights:** Helps hosts align listings with demand; renters can locate preferred room types.  

**8. Dashboard Name: Price Distribution by Borough**  
- **Target Audience:** Hosts  
- **Purpose:** Show price trends by borough.  
- **Actionable Insights:** Hosts can align pricing strategies with borough-specific trends.  

**9. Dashboard Name: Top 10 Hosts**  
- **Target Audience:** Hosts  
- **Purpose:** Identify top hosts by listings and pricing.  
- **Actionable Insights:** Understand successful hosting strategies.  

**10. Dashboard Name: Host Review Rating**  
- **Target Audience:** Hosts and renters  
- **Purpose:** Show host ratings and their impact on prices.  
- **Actionable Insights:** Ratings influence pricing; renters can prioritize highly rated hosts.  

**11. Dashboard Name: Availability by Month**  
- **Target Audience:** Hosts and renters  
- **Purpose:** Visualize seasonal listing availability.  
- **Actionable Insights:** Hosts can plan pricing; guests can find the best times for deals.  

**12. Dashboard Name: Amenities**  
- **Target Audience:** Hosts and renters  
- **Purpose:** Display common amenities and their impact on price.  
- **Actionable Insights:** Hosts can offer desirable amenities; renters can set expectations.  

**13. Dashboard Name: Room Type Distribution by Neighbourhood Group**  
- **Target Audience:** Hosts and Airbnb management  
- **Purpose:** Show room type popularity by borough.  
- **Actionable Insights:** Helps focus on in-demand room types by location.  

**14. Dashboard Name: Relationship Between Price & Availability**  
- **Target Audience:** Hosts and management team  
- **Purpose:** Analyze price-availability correlation.  
- **Actionable Insights:** Adjust pricing based on availability patterns.  

**15. Dashboard Name: Listings by Host & Neighbourhood Group**  
- **Target Audience:** Airbnb management  
- **Purpose:** Track host and neighborhood listing distribution.  
- **Actionable Insights:** Manage listing supply and identify high-concentration areas.  

---

**APPLIED DATA SCIENCE ASSIGNMENT 03**  
**MUSKAN PATEL**  

**PART II: Predictive Analytics and Visualization of Insights**  

---

### **Problem Statement**  

The primary objective of this project is to use predictive analytics techniques to analyze the New York City Airbnb rental market and identify relationships among variables. These insights can help Airbnb hosts optimize their pricing strategies, enhance guest satisfaction, and guide Airbnb management and policymakers in making data-driven decisions. By leveraging historical data, we aim to build predictive models and visualizations to uncover patterns and relationships between various features, such as pricing, reviews, availability, and location.  

By addressing the questions and relationships explored below, this project offers actionable insights to stakeholders, including Airbnb hosts, potential guests, and the Airbnb management team.  

---

### **Exploratory Analytics and Research Questions**  

Before predictive modeling, exploratory analysis was performed to identify meaningful relationships in the dataset. Some of the key questions explored include:  

1. What is the average price of Airbnb rentals across different neighborhoods in New York City?  
2. Which neighborhoods have the most listings and the highest occupancy rates?  
3. What is the relationship between price and the number of bedrooms or bathrooms in a listing?  
4. How do Airbnb rental prices vary across different seasons?  
5. Are there correlations between prices and guest reviews?  

---

### **Key Relationships to Explore**  

Based on exploratory analytics, the following relationships were identified for predictive modeling and visualization:  

#### **1. Relationship Between Price and Neighborhood**  
- **Dashboard Name:** Neighborhood vs. Price  
- **Target Audience:** Airbnb hosts and potential guests.  
- **Purpose:** To analyze the average price of rentals in different neighborhoods and identify trends related to pricing and occupancy rates.  
- **Information Presented:**  
  - Average price of property types in neighborhoods.  
  - Average price across top neighborhoods.  
  - Average price of neighborhoods over the years.  
- **Actionable Insights:**  
  - Hosts can adjust their pricing based on competitive analysis of average rental prices in their neighborhoods.  
  - Guests can identify affordable neighborhoods based on pricing trends.  

---

#### **2. Relationship Between Price and Reviews**  
- **Dashboard Name:** Reviews vs. Price  
- **Target Audience:** Airbnb hosts and potential guests looking for high-quality rentals.  
- **Purpose:** To explore how rental prices vary based on review scores in categories like cleanliness, accuracy, and communication.  
- **Information Presented:**  
  - Average price based on review scores for neighborhoods and neighborhood groups.  
  - Price trends by review scores across months and years.  
- **Actionable Insights:**  
  - Hosts can identify how improving reviews in specific areas (e.g., cleanliness) can impact rental prices.  
  - Guests can choose listings with high review scores while balancing their budget.  

---

#### **3. Relationship Between Price and Time**  
- **Dashboard Name:** Time vs. Price  
- **Target Audience:** Airbnb hosts and guests looking to plan bookings around specific times of the year.  
- **Purpose:** To analyze seasonal and temporal variations in pricing.  
- **Information Presented:**  
  - Average price trends over the months of the year.  
  - Price variations by years and days of the week.  
  - Impact of minimum nights and availability on pricing.  
- **Actionable Insights:**  
  - Hosts can optimize their pricing strategy based on demand fluctuations during different times of the year.  
  - Guests can plan bookings during low-demand periods for better deals.  

---

#### **4. Relationship Between Price and Host Characteristics**  
- **Dashboard Name:** Host vs. Price  
- **Target Audience:** Airbnb hosts, guests, and the Airbnb management team.  
- **Purpose:** To examine how host characteristics, such as response rates, number of listings, and superhost status, influence rental prices.  
- **Information Presented:**  
  - Average price of listings based on host characteristics.  
  - Top 10 hosts by neighborhood, listings, and average price.  
  - Correlation between host ratings and pricing.  
- **Actionable Insights:**  
  - Hosts can enhance their profiles to achieve better pricing (e.g., becoming a superhost or improving response times).  
  - Guests can assess how host characteristics affect pricing and make informed booking decisions.  
  - Airbnb management can use these trends to improve host training and support initiatives.  

---

### **Predictive Analytics Approach**  

The following predictive analytics techniques were applied:  

1. **Regression Models:**  
   - To predict the price of a rental based on features such as neighborhood, room type, number of reviews, and availability.  
   - Insights: Key factors influencing pricing can be identified for hosts to optimize their listings.  

2. **Correlation Analysis:**  
   - To understand the strength and direction of relationships between variables, such as price and reviews or price and neighborhood.  

3. **Clustering:**  
   - To group neighborhoods or listings based on pricing and availability trends.  
   - Insights: Hosts can identify high-performing neighborhoods, while guests can find budget-friendly clusters.  

4. **Time-Series Analysis:**  
   - To analyze seasonal trends in pricing and availability.  
   - Insights: Hosts can forecast demand and adjust their pricing strategies accordingly.  

---

### **Visualization Dashboards**  

#### **1. Neighborhood vs. Price Dashboard**  
- Displays average prices by neighborhood, property type, and top-performing neighborhoods.  
- Helps identify affordable areas and competitive pricing strategies.  

#### **2. Reviews vs. Price Dashboard**  
- Highlights the impact of review scores on pricing across different neighborhoods and months.  
- Enables hosts to focus on improving specific aspects to increase rental prices.  

#### **3. Time vs. Price Dashboard**  
- Showcases seasonal variations in pricing and availability trends across years and months.  
- Provides insights into high-demand periods for both hosts and guests.  

#### **4. Host vs. Price Dashboard**  
- Analyzes the relationship between host characteristics and pricing.  
- Helps hosts and Airbnb management identify successful strategies and areas for improvement.  

---

### **Actionable Insights**  

1. **For Hosts:**  
   - Adjust pricing based on neighborhood trends, reviews, and seasonal demand.  
   - Enhance host profiles (e.g., response rates and superhost status) to attract more guests.  

2. **For Guests:**  
   - Plan trips during low-demand seasons for cost-effective bookings.  
   - Choose rentals with optimal reviews and host characteristics based on their budget.  

3. **For Airbnb Management:**  
   - Identify trends in rental pricing and host performance to guide policy decisions.  
   - Offer training or incentives to hosts to improve guest satisfaction and revenue generation.  

---

This assignment combines exploratory analytics, predictive modeling, and dashboard-based visualization to deliver actionable insights for multiple stakeholders in the Airbnb ecosystem. By leveraging data-driven decisions, this project contributes to optimizing the New York City Airbnb market and enhancing user experiences.  

--- 
