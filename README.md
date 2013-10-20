Interactive Visualization
========================
#Data Domain
We started off by wanting to visualize some sort of data that would go well with a map. We restricted our scope to just the US and possibly think about the entire world as a final project. After some deliberation, we decided to visualize the trend of the state population from 1900 to 2010. The visualization would help us to compare the rate at which the population of various states varied in a similar time period. 

##Initial Concept and Storyboarding
The Interactivity that we aimed for
* Click on a particular state to get the trend.
* Click in the selected state again to deselect

![Storyboard1] (https://raw.github.com/haroonrasheed333/InteractiveVisualization/master/Screenshots/Screen%201.jpg)
![Storyboard2] (https://raw.github.com/haroonrasheed333/InteractiveVisualization/master/Screenshots/Screen%202.jpg)

###Additional features:
* Selecting between a bar graph and a line graph

##Final Visualization
[Live Visualization Link] (http://people.ischool.berkeley.edu/~haroon/CS294/Assignment3/interactive.html)


##Interactions
Upon opening, the svg of the entire US is displayed.   

![US Map] (https://raw.github.com/haroonrasheed333/InteractiveVisualization/master/Screenshots/A3US_Map.JPG)

##Data Selection

On selecting a state using a mouse click the line graph that shows the trend of the population in that state is displayed

'''Line Chart'''
![Line Chart] (https://raw.github.com/haroonrasheed333/InteractiveVisualization/master/Screenshots/A3LineChart.JPG)

'''Bar Chart'''
![Bar Chart] (https://raw.github.com/haroonrasheed333/InteractiveVisualization/master/Screenshots/A3BarChart.JPG)


##Graph selection

A check-box enables the user to select between 2 types of graphs, either a bar-graph or the line graph.

![Both Charts] (https://raw.github.com/haroonrasheed333/InteractiveVisualization/master/Screenshots/A3BothChart.JPG)

###Development stages and Individual contribution
We got the inspiration for the display of the map from [ http://bl.ocks.org/mbostock/2206590]. Though the map of the US was available based on the latitude and longitude, there was no state-name for us to work with, and that is precisely the key we wanted to use to get the data of the corresponding state from the csv file that had the population data. We had to spend some time figuring out a way to display the name of the states. We found the 

The next step was creating the line-graph and the bar-graph and enabling interactions to select between the 2. D3 to the rescue. Some small data conversions from a string to integer had to create the scales of both the x and y axes of the graphs. 

We kept our scope limited from the very beginning and were able to achieve pretty much what we wanted to in the end. We plan on extending our visualization for our final project and adding in information from different domains and bringing them together.


###Team
Haroon Rasheed Paul Mohammed

Bharathkumar Gunasekaran

The aspect that took the most time was getting to display the state name and integrating some javascript and d3 concepts. 

###Resources
Inspiration for map display and clicking : http://bl.ocks.org/mbostock/2206590

Data : http://data.worldbank.org/indicator/SP.POP.TOTL 

Map data: https://bitbucket.org/john2x/d3test/src/2ce4dd511244/d3/examples/data/us-states.json  

Line chart : http://bl.ocks.org/mbostock/3883245

Bar Chart : http://bl.ocks.org/mbostock/3885304
