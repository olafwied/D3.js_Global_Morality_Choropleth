This is a project for the Udacity Nanodegree "Data Analyst".
The visualization can be viewed at http://bl.ocks.org/olafwied/2edfd7c442667552849d

Summary: 

This figure shows how views on moral questions depend on where you live. 

The data shown here provides survey responses of different countries for the following three questions on marriage:

"Do you think ...

1) premaritial sex
2) divorce 
3) extramaritial affairs 

... are/is morally acceptable or unacceptable?

The question of premarital sex provides an excellent example on how moral questions are seen differently in different regions around the world.

Source: http://www.pewglobal.org/2014/04/15/global-morality/ (there are a lot more questions)

Design: 

Here, I used a thematic map where countries are shaded proportional to the level of rejection among the country's population (% of people who think the discussed issue is morally not acceptable).

A diverging cholor scheme (from red "unacceptable" to green "acceptable/not a moral issue") is used. 

Indivual values can be viewed by hovering the mouse over a country.

Feedback:

For my initial version (http://bl.ocks.org/olafwied/f01f2acae8b34c40790e) I received feedback from several people. In particular, that the stacked bars were hard to see and compare among countries or regions. I have to agree that a choropleth is the better (and simpler) design choice. 


Resources: 

mercator map and interactions: 
https://www.udacity.com/course/data-visualization-and-d3js--ud507

choropleth d3.js example: 
http://bl.ocks.org/mbostock/3306362

color scheme:
http://colorbrewer2.org 
