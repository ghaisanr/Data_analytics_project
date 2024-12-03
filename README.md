<h1> [Project New York City TLC Trip] </h1>

Project Overview:
This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus of this project is [NYC TLC Problem Statements] (Understanding customer demand patterns and optimizing taxi demand, improving vehicle distribution efficiency, and so on).

Main Objectives:
Objective 1: Understand the patterns of taxi demand throughout the day.
Objective 2: Identify the factors influencing taxi demand on specific days and analyze the differences in taxi demand at different locations, such as airports, downtown areas, or suburban regions.
Objective 3: Identify and adjust dynamic pricing to avoid negatively impacting revenue or customer satisfaction, while maintaining a balance between supply and demand.
Objective 4: Analyze the factors influencing customers in tipping drivers.

## 2. Data Sources
- [Dataset 1](https://drive.google.com/file/d/1jqTl_lO9RHhIC44m7GN7xHCRD7be5EZM/view?usp=drive_link) - (yellow taxi trip data on Januari 2023 dataset)
- [Dataset 2](https://drive.google.com/file/d/1LR-FJx2-DnIYJTe24WSPrbHoWf5SI6wV/view?usp=drive_link) – (Location for new york city)
- [Dataset 3](https://drive.google.com/file/d/19-eMW-joA1TQIyFLkxR8meMdoWwbd_iE/view?usp=drive_link) – (Geojson for borough new york city)
- [Dataset 4](https://drive.google.com/file/d/1VyUrmpQE1zSL7meYGhposEVQaKNY3udZ/view?usp=drive_link) - (Geojson for zone new york city)

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy)
- statistic model: scipy
- machine learning: scikit-learn
- Visualization: Matplotlib, Seaborn, Plotly
- Interactive Dashboard: Tableau
- Version Control: Git
- Others: Jupyter Notebook, missingno
## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks and tableau files.
│
├── reports            <- Generated analysis as PowerPoint, PDF.
|   ├── slide          <- Generated PowerPoint (pdf)
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight
1. Taxi Demand in January:
- In general, taxi demand showed a consistent pattern throughout January, with higher demand during weekdays and a decline in demand during weekends.
- The peak of demand occurred in the afternoon, while the lowest demand was recorded from midnight to early morning. Manhattan recorded the highest demand, while Staten Island showed the lowest demand among other areas.
- Customers more often use taxis with in-city fares through street-hail (waiting for a taxi on the street) and more frequently pay with credit cards or cash.

2. Pricing Impact on Taxi Usage:
Lower prices tend to encourage more people to use taxi services, but it is also possible that higher prices do not significantly reduce demand.
3. Factors Influencing Tips:
- Tips can be influenced by factors such as location, distance, time, number of passengers, and total payment.
- Trips to the airport tend to receive higher tips due to the longer distance and travel time.
- The longer the distance, the higher the tip given.
- The longer the trip duration, the higher the tip given.
- Weekends and holidays can lead to higher tips.
- The more passengers, the higher the tip tends to be.
- The higher the total payment, the higher the tip given.
### 5.2 Actionable Recommendation
1. Increase vehicle distribution in high-demand zones, such as Manhattan and Queens, during peak hours in the afternoon and evening. With the street-hail system, this can help drivers benefit more, such as receiving higher tips.
1. Offer discounts or promotions to implement dynamic pricing that can attract more customers during off-peak hours or non-busy times. Lowering prices during slower periods can encourage more people to choose taxis. Conversely, slightly higher fares in high-demand zones (such as airports or Manhattan) can be acceptable to customers if the service remains fast and convenient.

## 6. Contact
- Name: Ghaisan Rabbani 
- Email: ghaisanrabbani5@gmail.com
- Linkedin: linkedin.com/in/ghaisanr