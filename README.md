# Sleep-Quality-Analysis
Analyze a sleep-quality dataset to uncover how lifestyle, health, and demographic factors relate to poor sleep. Identify key predictors of sleep issues and provide data-driven recommendations for improving sleep.

Coefficients: [Stress LEvel Heart Rate]
Coefficients: [-0.37833747 0.00940953]
Stress Level (-0.378)
For each one-unit increase in stress level, the predicted quality of sleep decreases by 0.378 units, assuming heart rate stays constant. Higher stress lowers sleep quality.
Heart Rate (0.009)
For each one-unit increase in heart rate, the predicted quality of sleep increases by 0.009 units, assuming stress level stays constant. However, the impact of heart rate on sleep quality is very small.
Conclusion
The linear regression models provide more details about how much our correlated features impact sleep quality. We have the following conclusions:
1. The attributes most correlated with sleep quality are sleep duration, stress level, and heart rate. More specifically:
For each extra hour of sleep (up to 8.5 hours), quality of sleep improves by about 7% For each unit increase in stress level (on a scale of 1-10), quality of sleep decreases by about 3% For each unit increase in average heart rate, quality of
sleep decreases by about .4%
2. Clearly sleep duration is important for improving sleep quality. So what are the factors that impact sleep duration?
For each unit increase in stress level, sleep duration decreases by about .4 hrs (24 minutes) For each unit increase in average heart rate sleep duration increases by .009 hrs, or approximately .5 minutes
3. In terms of occupation, scientists and salespersons had the lowest quality of sleep ratings, while engineers had the highest.
Recommendations
If you have beens struggling with low quality sleep, consider the following recommendations:
Scientists rated their sleep quality an average of 5 out of 10, while engineers scored theirs much higher at 8.4 out of 10, showing a noticeable difference. Perhaps it’s time to rethink your career path?
The amount of sleep you get is the key factor in enhancing sleep quality. One way to extend your sleep is by reducing stress levels.
Although it's less significant, heart rate also influences both sleep quality and duration. Lowering your average resting heart rate can lead to improvements in both areas.
