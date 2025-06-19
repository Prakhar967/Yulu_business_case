# Yulu Business Case 

This project focuses on **exploratory data analysis (EDA)** and **business insights** for Yulu – a micro-mobility rental platform. The goal is to analyze customer behavior and identify key factors affecting usage and engagement.

---

## Objectives
- Understand customer usage patterns
- Identify peak usage hours and locations
- Perform hypothesis testing to validate assumptions
- Provide actionable business insights

---
## Column profiling

- datetime: datetime
- season: season (1: spring, 2: summer, 3: fall, 4: winter)
- holiday : whether day is a holiday or not
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
- weather:
  -- Clear, Few clouds, partly cloudy
  -- Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  -- Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  -- Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog
- temp: temperature in Celsius
- atemp: feeling temperature in Celsius
- humidity: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- count: count of total rental bikes including both casual and registered

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## Key Insights
- Found that weekday usage is significantly higher than weekend usage
- Identified top 3 zones with highest rentals
- Hypothesis test confirmed that average ride duration varies by day of week

---

##  Files
- `Yulu_case_study.ipynb` – google colab with full analysis
- `README.md` – Project overview and results

---

##  How to View
You can open the notebook directly in Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Prakhar967/Yulu_business_case/blob/main/Yulu_case_study.ipynb)

## 👨‍💼 Author
**Prakhar Asthana**  
Data Analyst | Python, SQL, Tableau , Numpy , Pandas , Hypothesis testing 
[LinkedIn](https://www.linkedin.com/in/prakhar-asthana-5b3a8b131/) | [Portfolio](https://github.com/Prakhar967/Yulu_business_case)
