# Air-Grace-Customer-Satisfaction-Analysis

<img width="1892" height="802" alt="DASHBOARD-GIF" src="https://github.com/user-attachments/assets/e5798ab2-a475-4615-901a-53914094a738" />

### Highlight: Only 43% of passengers are satisfied despite 82% being loyal customers, highlighting a major service quality gap.
---

<br> <br>

## INTRODUCTION

This project analyzes service ratings and customer satisfaction for the airline Air Grace, providing insights into the various services offered to passengers during their journey. The data has been collected from over 100,000 passengers across different age groups, genders, customer loyalty levels, travel classes, and flight distances, who rated various services on a scale of 1 to 5 after their journey.

__Note: The dataset used for this analysis was sourced from Kaggle.com. "Air Grace" is a fictional name and is used solely for presentation purposes.__

---

<br> <br>

## OBJECTIVE

➤ To analyze passenger satisfaction and identify key service gaps across customer segments.

➤ To evaluate satisfaction trends by travel class, loyalty, age group, and flight distance.

➤ To uncover the gap between loyalty and satisfaction and provide actionable recommendations to improve customer experience.

---

<br> <br>

## KEY INSIGHTS

### 1. Severe Service Gap Despite High Loyalty

<p align="center">
  <img src="https://github.com/user-attachments/assets/d566b997-09ca-43cb-8f14-056350ef8fbc" width="600">
</p>

Over 81% of passengers are loyal...

<p align="center">
  <img src="https://github.com/user-attachments/assets/248cc678-0a5b-49c8-ab70-9e726ae35b1d" width="600">
</p>

...yet only ~43% are satisfied, revealing a major disconnect between brand loyalty and actual service experience.

<br> <br>

### 2. Inflight WiFi is the Primary Driver of Dissatisfaction

<p align="center">
  <img src="https://github.com/user-attachments/assets/ec3b422c-15b7-4b12-919f-fd67955c3feb" width="600">
</p>

Inflight WiFi Service is consistently the lowest-rated service across nearly all segments (class, age, gender, distance), making it the single biggest opportunity for improvement.

<br> <br>

### 3. Satisfaction Strongly Correlates with Travel Class

<p align="center">
  <img src="https://github.com/user-attachments/assets/3916eee8-9c35-444d-b1f0-4a81b73c306b" width="600">
</p>

There is a sharp divide in experience:

➤ Business Class: ~69% satisfied 

➤ Eco Plus: ~25% 

➤ Economy: ~19% 

This highlights a significant inequality in service quality across classes.

<br> <br>

### 4. Longer Flights Drive Higher Satisfaction

<p align="center">
  <img src="https://github.com/user-attachments/assets/5286da8b-6868-4802-b4ad-172f5190085c" width="600">
</p>

Passenger satisfaction increases with distance:

➤ Long-haul: ~78% satisfied 

➤ Medium-haul: ~64% 

➤ Short-haul: ~33% 

This suggests premium experience consistency improves over longer journeys, while short-haul experience lags.

<br> <br>

### 5. Mid-Age Segment (31–50) Drives Both Volume and Satisfaction

<p align="center">
  <img src="https://github.com/user-attachments/assets/77229374-5816-4468-a46c-2d938aa76491" width="600">
</p>

Largest customer segment

Highest satisfaction rate (~51%) 

This group represents the core customer base and strongest value segment.

---

<br> <br>

## BUSINESS IMPROVEMENT RECOMMENDATIONS

<br> <br>

### ➤ Loyal customers are at risk

Over 52% of loyal customers are dissatisfied, signalling a high retention risk. Immediate focus should be on improving key digital and onboard services such as Inflight WiFi, Online Booking, Online Boarding, and Inflight Entertainment.

<br> <br>

### ➤ Digital experience is outdated

Low ratings for Ease of Online Booking, even among 18–30 year olds, indicate outdated platforms. Upgrading the website and app to deliver a simple, intuitive, and modern booking experience contributes towards travel excitement for the customers.

<br> <br>

### ➤ Airport experience impacts satisfaction

Low ratings for Gate Location suggest issues with accessibility and passenger convenience. Improving gate allocation strategy and overall gate experience can significantly enhance satisfaction.

<br> <br>

### ➤ Premium customers expect premium tech

Business Class passengers are dissatisfied with onboard technology, particularly WiFi and Entertainment. As high-value customers, their expectations for reliability and modernity must be met to protect brand perception.

<br> <br>

### ➤ Economy segment is a major risk area

With over 80% of Economy passengers dissatisfied, there is a serious threat to the airline’s largest customer base. Addressing core pain points: WiFi, Booking, Boarding, Entertainment, and Gate Experience is essential.

---
<br> <br>
## CONCLUSION

Air Grace must prioritise reducing dissatisfaction among both high-value segments (Loyal Customers, Business travellers) and high-volume groups (Economy passengers, mid-aged customers). Closing the satisfaction gap across segments, particularly between Economy and Business classes and Short-Haul and Long-Haul travellers, through targeted improvements in underperforming services will be critical to driving overall performance.

---
<br> <br>

  ## TOOLS USED

➤ Microsoft Excel

➤ Data Cleaning & Transformation

➤ Data Visualization (Dashboard Design)

---
<br> <br>

## METHODOLOGY

### 1. Data Preparation : Cleaned and structured the dataset of 103,904 passenger records

<br> 

### 2. Feature Engineering

➤ Created derived fields including:

 <p align = "center"> AGE GROUPS (0–17, 18–30, 31–50, 51–70, Above 70) </p> 

  <p align = "center">
  <img src="https://github.com/user-attachments/assets/7d2e39d3-7095-47e4-a9ac-a06e7db3d63f" height="600">
  </p>

<br>

<p align = "center"> DISTANCE CATEGORIES (Short, Medium, Long Haul) </p> 

 <p align = "center">
  <img src="https://github.com/user-attachments/assets/ffb5ed8d-353e-4577-8e9e-954d295e0c32" height="600">
  </p>

<br>

➤ Built calculated metrics such as:

<p align = "center"> CUSTOMER COUNT </p> 

  <p align = "center">
  <img src="https://github.com/user-attachments/assets/836d3094-e830-40e9-a5ec-da59ab6781b9" width="600">
  </p>

<br>

<p align = "center"> SATISFACTION RATE (%) </p> 

  <p align = "center">
  <img src="https://github.com/user-attachments/assets/51989c74-7729-4e3c-bcf6-3a0a573ec3de" width="600">
  </p>

<br>

<p align = "center"> AVERAGE SERVICE RATINGS </p> 

  <p align = "center">
  <img src="https://github.com/user-attachments/assets/69409864-b4d4-4336-8286-67b873bc2b3d" width="600">
  </p>

  <br>

  ### 3. Dynamic Filtering Logic: Implemented interactive filters using Data Validation dropdowns

   <p align = "center">
  <img src="https://github.com/user-attachments/assets/b6b70144-56b3-4098-a5a3-83132603ce66" width="600">
  </p>

<br>

### 4. Analytical Approach

➤ Performed comparative analysis across key dimensions:

* Customer Loyalty

* Travel Class

* Flight Distance

* Age Group

* Gender

<br>

➤ Identified patterns in satisfaction and service ratings to uncover:

* Underperforming services

* High-risk customer segments

* Opportunities for business improvement
<br> <br>
---















