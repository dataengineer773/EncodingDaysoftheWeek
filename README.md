We have a vector of dates and want to know the day of the week for each date, Use pandas’ Series.dt method day_name(), If we want the output to be a numerical value and therefore more usable as a machine learning feature,
we can use weekday where the days of the week are represented as an integer (Monday is 0), Knowing the weekday can be helpful if, for instance, we wanted to compare total sales on Sundays for
the past three years. pandas makes creating a feature vector containing weekday information easy.
