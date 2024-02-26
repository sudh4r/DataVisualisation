While scouring the internet for a dataset, I stumbled upon PwC's Power BI forage case studies that have a set of data analysis tasks about a call centre. Task 1 : Call Centre Trends requires the analyst to find various vital insights and create a dashboard showcasing these details. I identified the below six KPIs that will help stakeholders make data-based decisions to improve the call centre day to day operations. 
* Total Daily Calls
* % Answered Calls
* % Resolved Calls
* Average Response Time in Seconds
* Average Call Time in Minutes
* Average Rating
  
I also came up with a target value for these factors. If the actual value drops below the target value, the KPI will be highlighted in RED color. Numerous other visuals were also built based on these KPIs.
 
One challenge that I encountered was how to display line charts of the KPIs over time based on the dropdown selection. Creating five individual visuals is time-consuming and Power BI overlays visuals over one another. Therefore, only the recent visual will be interactive, and the others will not be. That's not ideal. That's when I came across this neat feature called 'Fields Parameter,' released as part of the May 2022 release. What a breeze it was. All I needed to do was create a parameter by dragging the relevant measures and then drop this parameter into the respective axis of the visual. Voila, I got a slicer and a single-line chart that plots corresponding data based on the option selected on the dropdown slicer :)

The other two tasks also looked interesting, can't wait to get started on those. 

PwC Forage Link : https://www.theforage.com/simulations/pwc-ch/power-bi-cqxg

Task Github Link : https://github.com/TimKong21/PwC-Switzerland-Power-BI-in-Data-Analytics-Virtual-Case-Experience

Here is the final output of the report.

![image](https://github.com/sudh4r/DataVisualisation/blob/dev/CallCenterTrendAnalysis/CallCentreAnalysis.png)

2. Netflix Report - Final Output

![image](https://github.com/sudh4r/DataVisualisation/blob/dev/NetflixReport/NetflixReport.png)
