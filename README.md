# Analysis on Lyft's Bay Wheels Bike Sharing Business

This dataset originally consisted of more than 4.7 million bike trips and spanned over a 2-year time frame. Main attributes included distance, duration, time of usage (day of week, time period, hour), user type (subscriber/customer) and Bike Share for All* enrollments. 500,000 data points were removed from this analysis due to missing or inaccurate information.

*The Bike Share for All program is offered to Bay Area residents on a limited income.
## Results
+ [lyft_baywheels_analysis.ipynb](https://github.com/sclkan/Lyft-Analysis/blob/master/lyft_baywheels_analysis.ipynb) (Full Code)
+ [Summary Report](https://github.com/sclkan/Lyft-Analysis/blob/master/lyft_baywheels_explanatory_report.ipynb)

## Summary of Findings
In this investigation, we focused on Lyft’s bike-sharing business by analyzing the usage frequency, distance, and duration. We also examined how factors such as the time of usage, user type and Bike Share for All enrollment could affect the aforementioned variable. 

Overall, peak hours are from 8:00 - 9:00 and 17:00-18:00 on weekdays. We can see that usage drops significantly after midnight and weekend traffic is mundane in comparison.  The relationship is linear between duration and distance after both variables undergo the logarithmic transformation.  This indicates that a percent increase in duration affects the percent increase in distance.



## Source
[Lyft's data hosted on AWS](https://s3.amazonaws.com/baywheels-data/index.html)

## Python Libraries
Pandas, NumPy, Matplotlib, Seaborn, Zipfile
