# baseball-hit-quality
Utilizing various baseball metrics to predict outcome of a hit and a weight hit quality metric:
1.*Baseline*: The first RMD file "baseball-hit-quality-regression-model" utilizes multinomial logistic regression for classification for predicting the result of a hit based on exit speed, bearing, angle, pitch type and the hit type. I used chi-squared and other data analysis tools to decide on the appropriate features for the model. The final model had an accuracy of 83.4%. Please refer to the HTML file for graphs and explanations.
2. The second RMD file "weighted-quality-hit-metric' aims to produce a metric that grades a hit based on the weight of specific metrics on hit outcome. For example, weighting "pitch type" more than "launch angle" in the metric as that is more important to play result. To view how I scored each metric's influence on hit quality please view the associated HTML file. This is an ongoing project. 


Idea: Weighted model that assigns a weight based on:
- Pitch type- higher weight for more difficult pitches
- Distance- higher weight for farther hits
- Bearing- Higher weight for left field hits
- Exit Speed- Higher weight for higher speed
- Hit type- Are their hits results in plays?
- Launch angle- 45 degrees is highest, lower for above and below
- Outcome of the hit- Higher weight for 1B-HR
