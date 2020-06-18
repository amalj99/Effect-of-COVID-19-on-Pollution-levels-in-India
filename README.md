# Effect of COVID 19 on Pollution levels in India

**PLEASE NOTE**:
Plotly graphs are rendered as static images only, as Github does not allow dynamic rendering.The complete notebook with interactive plotly plots can be found at https://nbviewer.jupyter.org/github/amalj99/Effect-of-COVID-19-on-Pollution-levels-in-India/blob/master/Analysis-EDA.ipynb.

## Objective
Our objective is to determine whether the lockdown that came into effect on 25th March, 2020 in India as a response to the COVID-19 pandemic, made a difference to the overall pollution levels in the country. We have access to a large database containing pollution data dating from 1st January 2015 to 1st May 2020.


## Code and Resources used
* Python Version: 3.7
* Packages used: Pandas, Numpy, Matplotlib, Seaborn and Plotly
* Data: https://www.kaggle.com/rohanrao/air-quality-data-in-india

## Data Description
The dataset conatins 26219 rows containing daily entries for 12 different pollutants for 24 cities. It also contains the AQI and AQI Bucket values for each entry.

## Observations
![](https://github.com/amalj99/Effect-of-COVID-19-on-Pollution-levels-in-India/blob/master/PM2.5%20levels%20in%20cities.png)

* The above plot shows the cities with the highest PM2.5 levels in the country.

![](https://github.com/amalj99/Effect-of-COVID-19-on-Pollution-levels-in-India/blob/master/AQI%20levels%20barplot.png)

* This plot shows the daily AQI levels in various major cities from 1st January 2019 to 1st May 2020.
* The black line represents the date when lockdown came into effect. 
* We can see a visible decrease in AQI levels after this date when compared to the same time period in 2019.

## Conclusion
* Using various visualization methods we can conclude that the overall pollution level in multiple cities across the country did decrease after the nationwide lockdown was enforced.
* We also witnessed certain trends with respect to the time of year, which govern the overall pollution concentrations in the country.




