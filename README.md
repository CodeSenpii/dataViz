Kieyn Parks
CS-498 Data Visualization.
Summer Session 2020

Gun Crime Statistics in America

The visualization is an interactive slideshow ordering using data gathered from the US Federal Beau of investigations (FBI). The Visualizations will explore gun crime statics by state. Gun crime has historically plagued metropolitan cities and urban areas of the United States for many decades. In this presentation we will explore three years of data from 2016-2018.
I choose this dataset because I was intrigued to see how the fight against gun crime is progressing overall and if gun crime is shifting from state to state as the crackdown continues? The presentation also explores crimes with other types of weapons.
The raw data had to be clean of extraneous information converted to csv and json to be consumed by D3.js.
Elements of Narration
The website was created using D3, HTML, CSS and JavaScript. The website has elements of scrolling, transitions, navigation bar, multiple scenes, triggers, and tool tips. The visualizations utilize bubble charts, bar charts and a choropleth to illustrate the data.
Scenes: 
Each chart has three scenes. Each scene represents a year of data from 2016-2018 and the user can interact with each scene in sequence or randomly. Also, the visualization presents the map chart fist. This is the most visually effective as it outlines to the user each state in plain view which the user can play around with at random.

Annotations:
Annotations, filters and labels are used to deliver the information to the user and guide the reader into the data without being overwhelming.
Affordances: 
The affordances that enable the user to know what services are available to them are raised buttons, borders, labels and color gradients. These ques prompt the user to interact with the charts. For example, the button on the charts are raised as a hint they can be pressed. The Choropleth are filled with state border lines to hint to the user that an interaction is possible.
Parameters & Triggers:
The primary parameter of the narration is the total number of murders by state, region, and by the type of weapons used in the commission of the crime. For example, handguns have caused a lot more murders than knives and other types of weapons using the tool tips functionality to delineate these finding. Color gradient and size is also used as a visual que to quickly indicate to the reader differences state by state.  For example, you can very quickly see the differences between New York and California without moving the mouse along the chart. The user can further explore the information by hovering the mouse over a selection for the tooltip info.
Charts:
This narration contains 3 types of charts
•	Bubble chart: two scenes per year (Cumulative, by region) with tooltips and transitions
•	Map of the United States (48 contiguous states) with tool tips
•	Bar chart with tool tips
The bubble chart and Map charts indicates the same type of information and gives the user more flexibility to understand the information visually. The bar chart gives an overall view of the types of weapons used in total. The most favorite weapon to commit crime is by for handgun. 
The Gun Dataset
The latest data from the FBI's uniform crime reports provides a fascinating picture of the use of firearms in crimes across America. The Gun crime dataset really gives in depth information on different types of crimes which involved: Handgun, Rifles, Shotguns, Firearms (type unknown), Knives or cutting instruments and Other weapons. Furthermore, you will see a trend in murders from 2016 to 2018 where crimes in the US continue to rise and the data will vary based on the population in each state. Congress failed to act and The National Rifle Association, the largest and most influential of the gun rights lobby groups, has been similarly silent after each massacre and the murder figures themselves are astounding for a country like the United Kingdom its used to around 550 murders per year. In 2018 - the latest year for which detailed statistics are available - there were 16,214 murders in the US. Of those, 8,583 were caused by firearms. The FBI crime statistics are based on reports to FBI bureau and local law enforcement. In conclusion, I am very passionate about the gun debate and this is why I chose this dataset in order to show that if we have that we need to have gun reforms in the US. This is not a matter of the second amendment rights but rather a matter of life and death.
Ref:
www. https://catalog.data.gov/dataset?tags=crime



References and Resources

Github Project
	

Dataset
	Gun Crime Dataset

Bubble Chart
	Bubble Chart d3 v4 Github Gist by John Alexis Guerra Gomez
	Animated Bubble Chart by Jim Vallandingham


Bar Chart
	Bikram

https://codesenpii.github.io/dataViz/#
