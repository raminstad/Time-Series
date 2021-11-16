# The goal of this paper/project is to determine and predict the total number of goals in the next two years in the premier league (England's league). The reason that I used England versus other quality leagues like Spain or Germany is because the premier league is the most competitive league in the world and teams in the league have been almost the same in terms of playing style and the amount of goals that they scored. Meaning that the forecasting model will be the most accurate in such leagues which consistency is present versus a league like Spain where the only two good teams are Barcelona and Real Madrid and every year that they win the league and other teams in the league are not consistent in terms of scoring goals and competing with these two giant clubs and this makes predicting for this league extremely hard, or perhaps the forecast model will not be accurate at all.The data which I have collected comes from a library in R called worldfootballR, this library is immensely useful for people who want to perform soccer analysis for data science, and it is extremely user friendly, one would just look at their documentation and they will explain what parameters we need to enter to get the right dataset. For this project I needed to get twenty years of data from the 1999/2000-2020/2021 season meaning that I had twenty two datasets to work for and do cleaning on it. The twenty two datasets which I collected were all in a same format with the same amount of columns and rows and the only difference in them was that they were from different years, the columns that I wanted to keep and work on were only two columns and they were the date and goals columns and I dropped the rest, then I combined all twenty two datasets, for the full representation of how my dataset looked before, during, and after cleaning I wrote an article about this project which you can check it out in here: https://medium.com/@ramram007/time-series-analysis-on-total-premier-league-goals-36488fdebcf2#10f0-75f1cf1153eb. My research question for this project was how many goals will be scored each month from JAN 2021-DEC 2022 in premier league, therefore after doing an exorbitant amount of research I came to a conclusion that the best model that I can make is via time series analysis, I made my model using ARIMA and forecast total premier league goals for JAN 2021-DEC 2022 months, the reason that I did model for the months that has already been passed was to compare the point forecast from the model and see if the real data being goals scored in passed months will be in the interval range of my model, and it turned out after comparing the real data vs my model they were very close and were in the interval range for example the real data for AUG 2021 is eighty five goals and my model predicted seventy goals which was in the interval range of 36-104 goals for the %80 conf interval, you can see the comparison of other months in the article which I mentioned :https://medium.com/@ramram007/time-series-analysis-on-total-premier-league-goals-36488fdebcf2#10f0-75f1cf1153eb. In conclusion this was my first time using time series analysis and I only researched about this method for twenty days, and I know that there are so many details about time series analysis which makes it impossible to fully master it in this short period of time, but I feel like I got a clear understanding of the math behind it and when we can or we cannot use this method and I really enjoyed performing this type of analysis on my arera of interest.