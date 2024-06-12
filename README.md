# Chicago-Crime
* We have prepared a zip file with the Chicago crime data which you can download: https://drive.google.com/file/d/1avxUlCAros-R9GF6SKXqM_GopzO7VwA5/view
* Original Source: Chicago Data Portal: Crimes 2001 to Present
   -  Data Description:
        All Crimes that were reported in the city of Chicago and their details View Preview: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/data

# Stakeholder Questions
##  Which district had the most crimes in 2022?
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/1c5062ca-354b-4e3c-8876-1e9557b02b53)
*  Upon analysis, it was found that zones 6 and 8 had the highest number of darts during 2022
## Is the number of crimes increasing or decreasing over the years?
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/6881a707-ea13-4ded-ad9f-94e33025ef5c)
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/3ce3fce6-ae06-43cd-a972-40b59647201c)

 * Based on the available analyses, the number of crimes in these areas has decreased over time. This trend can have significant implications for general security stability or the effectiveness of security measures that have been implemented. It is beneficial to monitor this trend over time to understand the influencing factors better and make strategic decisions accordingly.
## What months have the most crime? What months have the least?
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/aeebba26-3064-43f4-9de6-24fb9dbd50d1)
![crime_trends](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/0ede4794-0786-4b04-b2cf-5d70268ffee3)

## What are the top 3 holidays with the largest number of crimes?
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/0b65d858-5409-4340-a374-9a8ea9b42f1e)

## For each of the top 3 holidays with the most crime, what are the top 5 most common crimes on that holiday? 
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/0c983109-d0d3-47cb-a5a9-a15101249015)
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/44499440-e03b-460d-88ad-1f3e1760198b)



# Forecasting Crime Models: 
In this section, we will create predictive models for various types of crimes based on the historical data available.
We will use a range of statistical methods and machine learning techniques to analyze patterns in the data and forecast future trends.

# ARIMA/SARIMA 

   ## Theft crimes:
    
  
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/252a8b5d-4c69-41c0-a4da-ba7408ade1b5)
   
   
 ###  Summary of forecast: 
 ![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/84fbc3ad-8b1d-410e-a035-573264aeaebf)

 * ARIMA(0, 0, 0, 1, 1, 2, 12)
         - MAE: 29.87
         - MSE: 1,397.176
         - RMSE: 37.379 
         - R^2: 0.162
         - MAPE: 26.41%
 *  ARIMA(0, 0, 0, 1, 1, 2, 12) is the best among the three models based on the AIC criterion, as it has the lowest AIC value. This indicates that it is the most efficient model in balancing prediction accuracy and complexity.


## Narcotics crimes: 
![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/9689f17a-41b2-4887-b4a2-88e84edb3744)


 ###  Summary of forecast: 
 ![image](https://github.com/ashrafabuareesh/Chicago-Crime/assets/123064338/610e321d-4534-40a0-8330-0ea04f269a19)

      - MAE: 10.640
      - MSE: 169.226
      - RMSE: 13.009
      - R²: 0.185
      - MAPE: 89.19%
      - AIC: 1960.191

  * The model  has a lower AIC (1960.191), This suggests that Model  offers a better fit with the data based on the AIC criterion.
  * Error Metrics:
     - Comparing the error metrics, the Model shows better performance with lower MAE, RMSE, and MAPE.
   
## Final Evaluation:

#### Change in Theft over the forecast period:

  * The change in theft is -9.58, indicating a decrease in theft-related crimes.
Percentage change in Theft:

   * The percentage change in theft is -8.56%. This indicates a noticeable decrease in theft crime rates.
#### Change in Narcotics over the forecast period:

* The change in narcotics is -15.92, indicating a sharp decline in narcotics-related crimes.
Percentage change in Narcotics:

* The percentage change in narcotics is -282.05%. This indicates a significant and dramatic decline in narcotics-related crime rates.
Based on these numbers:

#### Which type of crime is expected to have the highest monthly crime count at the end of the forecast period?

* Based on the change in theft, theft crime is expected to have the highest monthly crime count at the end of the forecast.
#### Which type of crime is expected to have the highest net change by the end of the forecast period?

* Based on the substantial decline in narcotics-related crimes, narcotics-related crime is expected to have the highest net change by the end of the forecast.
#### Which type of crime is expected to have the highest percentage change by the end of the forecast period?

* Based on the drastic percentage change in narcotics, narcotics-related crime is expected to have the highest percentage change by the end of the forecast.

# Final Recommendations:

* Given the analysis and forecasts, I recommend focusing on the following strategies for addressing crime rates:

 - Resource Allocation:

  * Given the significant decrease in narcotics-related crimes, reallocating resources from narcotics enforcement to community engagement or crime prevention initiatives may prove beneficial. This can help strengthen community ties and reduce crime rates further.
- Community Outreach:

  * To sustain the decrease in narcotics-related crimes, community outreach programs that focus on early intervention, education, and awareness can be established. This approach could help reduce the appeal of narcotics in the community.
- Continued Monitoring:

  * Continuous monitoring of both crime rates will be crucial. If any fluctuations are detected, the allocation of resources can be adjusted accordingly to maintain or enhance community safety.


   




