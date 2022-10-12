# Kickstarting with Excel
Module 1 Challenge 

## Overview of Project
The purpose of this analysis was to provide clarification to Louise on how other plays fundraising preformed compared to hers. Using the data that was provided we created a table and two-line charts for Louise to view the information from different analytical perspectives. Each perspective utilizes the data from successful, failed, and canceled plays to create a clearer outcome of how each one met their fundraising goals.

## Analysis and Challenges
One of the biggest challenges I faced was getting the “Outcomes Based on Goals” line chart to correctly read the data. Initially the chart wasn’t producing the outcome that I wanted, and I had to go back multiple times to fix it. 
  
My percentage successful was charting correctly, however the percentage failed was nowhere on the chart. Additionally, the percentage canceled which should have charted at 0% appeared to shoot up to 100%. After further investigation I discovered my formulas were affecting the overall results. Where as the formula should have been “=COUNTIFS(Kickstarter!F:F,"=successful",Kickstarter!Q:Q,"plays",Kickstarter!D:D,">=50000")”, I inputted it as “=COUNTIFS(Kickstarter!F:F,"=successful",Kickstarter!Q:Q,"plays",Kickstarter!D:D,">=50000",Kickstarter!D:D,"<More")” which caused the whole bottom row to produce incorrect information. After I had successfully corrected the formulas, my chart still wasn’t giving me the outcome I was looking for. In fact, after correcting the formula none of the information was charting at all. This resulted in me having to play around with the system some more and realizing I was going to have to manually account for the information myself. I was able to do this by opening the “Select Data Source” and input the correct values. This resulted in my line chart finally producing the outcome that was required for this assignment.  
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In conclusion the amount of successful fundraising campaigns was almost double of those that failed. I would also say base off the line chart the most successful fundraising campaigns happened in the summer months. 
- What can you conclude about the Outcomes based on Goals?
. I also noticed from the “Outcomes Based on Goals” chart that the campaigns that kept their goal more moderate had a higher success rate then the campaigns that didn’t. 
- What are some limitations of this dataset?
The methods in which fundrasing was done, and how many people particated in the campaign. Having that infomation may have been able to provide additional on how goals were met. 
- What are some other possible tables and/or graphs that we could create?
This information could have easily been adapted to a circle or bar graph 
