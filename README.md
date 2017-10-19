# P6-Data-Visualization-using-Titanic-data-DAND
Project 6 
Data Visualization using dimple.js and d3.js

Summary:
For my data visualization project I used the famous "Titanic" dataset which contains demographics and passenger information for 891 passengers out of total 2224 passengers and crew on board the Titanic. The data file contains information such as Passenger class (socio-economic status), Sex, Age, Number of Sibling/Spouse/Parent/Children travelling with them. 

The visualization is basically explanatory, displays the analysis and the statistics of people who died and survived based on their socio-economic status and their gender.


This project contains the visualization of the survivors in the Titanic disaster. It is an interactive visualization and consists of 3 charts which visualizes:

Survivors by Sex
Survivors by Passenger class
Survivors by age
Survivors by Age/Sex

Design:

I performed an exploratory data analysis on the titanic data set during project 2 of the data analyst nanodegree. Therefore, I used the results of the analysis for visualization.

I analysed the data using Pandas to find out the male and female survivors and accordingly I extracted the data into a csv file, and used bar chart to plot the visualization. I used dimple.js to render the bar chart and used svg to render the number of survivals on the bars of the bar chart. In the same way I visualized the survivals according to age.

For multi variable analysis, I visualized survivors by passenger class and sex and survivors by age and sex. And used legends to depict the sex of the passengers.

I created interactive buttons that will allow the user to filter and select the chart they want to view.

Feedback:

Feedback 1:
What do you notice in the visualization
If I click on the same button multiple times the same graph gets generated

What questions do you have about the data?
In graph 1 and 3, we see data on the bar  but not in graph 2. Shouldn't it be consistent?

You should show percentage of survivors instead of number

Feedback 2:
(1) When I first go into your website, I don't see any chart. I think it is better to represent "Survivors by sex" chart when reader refresh the website. 
(2) You should check the buttons. when I repeat click the button, the picture comes out one after another. I think every chart should represent in a fix place, and you forgot to clear the previous chart. 
(3) Button color should be initialized when you click another button.


Feedback 3:
Content:
I find it clear and easy accessible the way it is presented.
I notice that more males and that the group of 10-20 year olds had a low amount of survivors. But was that because fewer from those groups travelled with Titanic? I would consider adding percentages then perhaps it is easier to make some interesting points. I also notice that 2nd Class had a higher ratio of women versus men surviving - are 2nd class men more galant? Again, difficult to say only based on the numbers.

Color: 
Colorwise, I find the black on gray a bit hard to read. Perhaps a lighter text color could be used.
And could the color distinction between female and male also be used in the first chart?

Text:
The use of the phrase "survived more" does not sound correct to me - I would use "had a higher survival rate" (but note - I am not a native English speaker).

Interaction:
As noted in other feedback, then the plots are not cleared when you select them the 2nd time but they keep adding up.

Conclusion:

After exploring the data, these are my findings:

1. The females had a higher rate of survival compared to males. The reason for this maybe the women were prioritized first and were escorted to safety.

2. The passengers of class 1, survived more, maybe because, the first class cabins and suites were located over five decks, generally amidships, where the ship’s motion would be least felt.

3. The young children had a high survival rate, due to the most probable reason that the children alongwith their mothers were able to escape. Again, here I havenot factored by class but on analyzing the data, I found that the women and children of First class were among the highest survivors.

4. In the fourth chart, the young women between the age of 15-30 were the highest survivors.



Resources:

https://bost.ocks.org/mike/bar/
http://dimplejs.org/
https://github.com/d3/d3/wiki/Tutorials
https://w3schools.com/
http://www.d3noob.org/2013/02/update-d3js-data-dynamically-button.html
