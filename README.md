# Lyft's Bay Wheels Customer Analysis

Bay Wheels is a bike-sharing service in the San Francisco Bay Area owned by Lyft.  In this investigation, we focused on the behavior of its customers by analyzing their usage frequency, distance traveled, and trip duration.  We also examined how factors such as the time of usage, user type and Bike Share for All enrollment* could affect the aforementioned variables.

This dataset consisted of more than 4.7 million bike trips in the Bay Area and spanned over a 2-year time frame.  Main attributes included distance, duration, time of usage (day of the week, time period, hour), user type (subscriber/customer) and Bike Share for All enrollment.  500,000 data points were removed from this analysis due to missing or inaccurate information.

*The Bike Share for All program is offered to Bay Area residents on a limited income.
## Results

+ Full code: [here](https://github.com/sclkan/Lyft-Analysis/blob/master/lyft_baywheels_analysis.ipynb)
+ Summary report: [here](https://github.com/sclkan/Lyft-Analysis/blob/master/lyft_baywheels_explanatory_report.ipynb)
+ Slides created with Python: [here](https://github.com/sclkan/Lyft-Analysis/blob/master/lyft_baywheels_explanatory_report.slides.html) (please download to view)

## Key Insights

Overall, the peak hours were from 8:00 - 9:00 and 17:00-18:00 on weekdays. We saw that usage dropped significantly after midnight and weekend traffic is mundane in comparison.  The relationship is linear between duration and distance after both variables underwent the logarithmic transformation, meaning that a percent increase in duration would affect the percent increase in distance.

We also learned that an average bike ride was about 10 - 20 minutes and 1.2 - 1.8 kilometers.  When broken down by the day of the week, Friday evening and Saturday afternoon trips had the longest duration.  Surprisingly,  despite the higher per-minute rate, casual customers took farther and longer trips than Bay Wheels members on average.

## Source
[Lyft's data hosted on AWS](https://s3.amazonaws.com/baywheels-data/index.html)

## Python Libraries
Pandas, NumPy, Matplotlib, Seaborn, Zipfile
