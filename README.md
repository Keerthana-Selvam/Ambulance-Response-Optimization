# Optimizing Ambulance Response Times
This repository contains my MSc dissertation on optimizing ambulance response times for the Welsh Ambulance Service Trust (WAST) using machine learning and geospatial analysis. The study identifies critical bottlenecks in emergency medical services and proposes actionable strategies to enhance operational efficiency.

## Key Findings
This research leverages data-driven techniques to improve ambulance response times and provides actionable recommendations to the Welsh Ambulance Service Trust (WAST). Below are the major findings:

1. **Prediction of Response Times**:
   - Using the **XGBoost classification model**, the study achieved:
     - **Accuracy**: 66.89%
     - **Recall**: 94% for identifying scenarios where ambulances meet the 8.5-minute target.
   - Key predictors of response times included:
     - **Overall Traffic**: Urban areas faced delays due to heavy traffic congestion.
     - **Hour of Day**: Response times were slower during peak hours.
     - **Incident Priority**: Critical incidents were prioritized and achieved faster response times.

2. **Demand Forecasting**:
   - The **Prophet model** excelled in predicting ambulance demand during peak hours and special events, with:
     - **Mean Absolute Error (MAE)**: 4.50
     - **Root Mean Squared Error (RMSE)**: 5.85
   - The model identified:
     - **High-demand intervals** such as weekends and public events.
     - Seasonal patterns influencing ambulance usage.

3. **Geospatial Disparities**:
   - Significant discrepancies between urban and rural regions:
     - Urban centers like **Cardiff** benefited from better infrastructure and shorter response times.
     - Rural areas like **Powys** and **Ceredigion** consistently failed to meet response targets due to:
       - Extended travel distances.
       - Limited ambulance availability.
   - Geospatial heatmaps pinpointed underserved regions requiring additional resources.

4. **Influence of External Factors**:
   - **Traffic Congestion**: Urban areas experienced significant delays during rush hours.
   - **Weather Conditions**: Rain and poor road conditions in rural regions further exacerbated delays.
   - Integration of real-time traffic and meteorological data is recommended to enhance forecasting accuracy.

5. **Future Opportunities**:
   - Adoption of **blockchain technology** for secure, real-time data sharing among EMS stakeholders.
   - Use of advanced models like **LSTM networks** for sequential forecasting of demand.
   - Region-specific strategies to address unique challenges in urban vs. rural areas.

## Contents
- `Dissertation.pdf`: Full dissertation document detailing methodologies, results, and recommendations.
- `Figures/`: Visualizations and plots illustrating key findings.
- `References/`: Bibliography and additional resources.

## Recommendations for Improvement
This research provides several actionable recommendations:
1. Increase ambulance resources in underserved rural areas.
2. Incorporate real-time traffic and weather data for improved decision-making.
3. Implement blockchain-based systems for secure, transparent data sharing.
4. Optimize ambulance placement and routing using dynamic geospatial models.

## Contact
Feel free to reach out for collaborations or inquiries:
[keerthanaselvam0229@gmail.com](mailto:keerthanaselvam0229@gmail.com).
