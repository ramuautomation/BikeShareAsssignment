# Bike-sharing-assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

# General Information
   A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
   
## The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies Used
    •	Python - 3.11.7
	•	Anaconda - 2.5.2
    •	Pandas - 2.1.4
    •	Jupyter - 7.0.8
    •	NumPy - 1.26.4
    •	Matplotlib - 3.8.0
    •	Seaborn - 0.13.2
    •	statsmodels - 0.14.0
    •	sklearn - 1.2.2

## Conclusion

Significant features:
1. Year
2. Weather day is a holiday or not
3. Temperature
4. Wind speed
5. Season type
6. Months(January, July, September)
7. Weather situation: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

Comparison of R2 scores:
1. Train model R2 score is 0.8367
2. Test mode R2 score is   0.8023
3. Difference of 0.0344 is in acceptable range.

Residual analysis of Train and Test data
1. Both the plots are normally distributed
2. Both are centered around 0

**Contributer**
  •	Ramu Pallepati
