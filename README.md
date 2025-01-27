# Optimizing Ambulance Response Times
This repository contains my MSc dissertation on **Optimizing Ambulance Response Times** for the Welsh Ambulance Service Trust (WAST). The project leverages advanced machine learning techniques, geospatial analysis, and time-series forecasting to identify bottlenecks in emergency medical services and proposes actionable strategies to improve operational efficiency and patient outcomes.

---

## Key Findings
This research integrates cutting-edge data-driven methods to analyze and enhance ambulance response times, providing actionable insights for WAST. Below are the major highlights:

### 1. **Prediction of Response Times**
   - Developed a predictive classification model using **XGBoost**, which achieved:
     - **Accuracy**: 66.89%
     - **Recall**: 94% for identifying successful response times.
   - Key predictors influencing response times:
     - **Traffic Congestion**: A significant factor, especially during peak hours in urban regions.
     - **Hour of Day**: Response times increased significantly during rush hours and late afternoons.
     - **Incident Priority**: Critical incidents (e.g., cardiac arrests) were prioritized, leading to shorter response times.
     - **Geographical Factors**: Urban areas performed better due to shorter distances and infrastructure, while rural areas faced consistent delays.

### 2. **Demand Forecasting**
   - Utilized **Prophet**, a time-series forecasting model, to predict ambulance demand with:
     - **Mean Absolute Error (MAE)**: 4.50
     - **Root Mean Squared Error (RMSE)**: 5.85
   - The model identified:
     - **Peak Demand Times**: Weekends and late afternoons showed the highest number of incidents.
     - **Seasonal Variations**: Demand surges during public events and holidays.
     - Forecasting demand provided actionable insights for proactive resource allocation.

### 3. **Geospatial Insights**
   - Conducted geospatial analyses to identify underserved regions:
     - **Urban Centers**: Cities like **Cardiff** consistently met response time targets due to better ambulance density and infrastructure.
     - **Rural Regions**: Areas like **Powys** and **Ceredigion** struggled with long response times due to:
       - Greater travel distances.
       - Fewer ambulances available.
   - Generated geospatial heatmaps to pinpoint high-delay zones, enabling strategic ambulance placement.

### 4. **Impact of External Factors**
   - Explored the influence of real-world factors on response times:
     - **Traffic Conditions**:
       - Urban areas experienced delays during rush hours despite better infrastructure.
       - Dynamic routing based on real-time traffic data was suggested.
     - **Weather Effects**:
       - Rain exacerbated delays, particularly in rural regions with underdeveloped roads.
       - Weather forecasts can improve response time predictions.
   - Demonstrated the importance of integrating real-time traffic and weather data for operational decision-making.

### 5. **Modeling and Evaluation**
   - Built and evaluated advanced machine learning models to predict response times:
     - **XGBoost** emerged as the top-performing classification model due to its ability to handle imbalanced datasets and non-linear relationships.
     - Time-series forecasting using **Prophet** provided actionable predictions for ambulance demand planning.
   - Highlighted potential for adopting **LSTM networks** for sequential data analysis and improving forecast accuracy.

### 6. **Key Recommendations**
This research outlines several key strategies to optimize ambulance response times:
   - **Improve Rural Coverage**:
     - Reallocate ambulances to underserved rural areas based on geospatial analysis.
     - Establish satellite ambulance stations in high-delay zones.
   - **Leverage Real-Time Data**:
     - Use IoT-enabled traffic and weather monitoring for dynamic decision-making.
     - Real-time routing to avoid delays during peak hours and inclement weather.
   - **Implement Blockchain Technology**:
     - Enhance data sharing security and transparency among emergency stakeholders.
     - Use blockchain for real-time updates on ambulance locations, traffic, and hospital availability.
   - **Predictive Resource Allocation**:
     - Forecast ambulance demand to optimize staffing and vehicle distribution.
     - Dynamically adjust ambulance positioning during peak times.

### 7. **Future Opportunities**
The dissertation identifies innovative solutions to push EMS optimization further:
   - **Advanced Modeling**:
     - Adoption of **deep learning models** like LSTM for more complex demand forecasts.
     - Region-specific machine learning models for urban vs. rural challenges.
   - **Infrastructure Development**:
     - Invest in road networks and ambulance infrastructure in rural regions.
     - Explore telemedicine technologies to assist patients remotely during long travel delays.
   - **Dynamic Shift Scheduling**:
     - Optimize staffing and ambulance availability based on peak demand predictions (e.g., weekends, public events).

---

## Contents
- `Dissertation.pdf`: Full dissertation document detailing methodologies, results, and recommendations.
- `Figures/`: Visualizations and plots illustrating key findings.
- `References/`: Bibliography and additional resources.

---

## Recommendations for Improvement
This study emphasizes a data-driven approach to improving ambulance response times, and the following recommendations were made:
1. Increase ambulance resources and establish satellite stations in rural areas with high delays.
2. Integrate real-time traffic and weather data into operational systems for dynamic decision-making.
3. Implement blockchain technology for secure and efficient data-sharing among stakeholders.
4. Utilize demand forecasting models for proactive resource allocation and scheduling.
5. Address urban-rural disparities through tailored strategies, improving patient outcomes across all regions.

---

## Contact
For further inquiries, collaborations, or discussions, feel free to reach out:
[keerthanaselvam0229@gmail.com](mailto:keerthanaselvam0229@gmail.com)
