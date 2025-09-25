# 03
![[attachments/different_imputation_viz.png]]
energy consumption data over a two-day period

The data is moderately noisy. This is because it shows a clear temporal trend with overall consumption rising and then falling during the day with a small spike at 18:00 and being almost none during the night. During the day, the different imputation techniques show very different spikes.

So the most prominent pattern is a clear daily cycle

When we compare the consumption of today with the one from yesterday, we can see that the spikes vary alot which tells us, that the data is quite noisy but during the night its stable.

## Different Imputation strategies
hourly_profile captures the broad trend of low consumption at night and higher consumption during the day but misses the sharp peaks and volatility of the actual data. This approach is very generalized and therefore loses critical details but it's good to get a general feel for the trends.

prev_day_imputed copies the previous day's pattern. it gives us a good feelfor a realistic daily structure with peaks and troughs, it fails to account for day-to-day variability.

![[attachments/previous_day_viz.png]]
comparing **original data** to data imputed using a **"previous day" method**.
The data is quite noisy due to the sharp spikes. The previous day imputed is also far off during the spikes which shows inconsistency during these times. 

There are probably some "day of the week" effects because the spikes from the previous days look very different. The "calm" times look very similar though


The 7.10.2012 was a sunday so it's understandable, that the energy consumption is higher in the morning than on monday because the dataset we're reading from is the "London Smart Meters" which captures the energy consumption of households and on sundays there are more people at home than on mondays. The spike on monday 18:00 also nicely shows when the people come home from work

