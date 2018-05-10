# Traffic Congestion Indicator

It is a map which shows users the traffic congestion situation of North America and plays different music as a result of the amount of traffic incident. 

## Summary

The goal of my project is to use the technology to help people identify the traffic situation. After a user inputs the latitude and longitude range of an area in North America, the map will display the traffic congestion situation with numbers of red dots and play different music as a result of the amount of traffic incident. For example, When a user inputs the coordinates of California:25,-110,43,-125, the map will show lots of red dots on Log Angeles and the Bay Area. A similar situation happens in Chicago and New York, since both of them are big cities. As the number of incident is more than 50, user will hear the sound of car explosion. However, if the user inputs: 48,-140,70,-110, the coordinates of Canada, there are fewer red dots appeared. At this time, user will hear leisure sounds.


## Component Parts

On the hardware side, I will need my computer.

Keyboard (input)

On the software side,I will need mapbox to display the map and traffic data API.

mapbox(output) 
traffic data(input)
sounds(output)


## Challenges

Using the Json data and understanding the structure of the data is hard for me. The tutorial was using csv file, however, the traffic data API I found online is JSON or XML format. So I need to learn about the JSON and XML data. 

## Timeline

- Week 1: Write proposal
- Week 2: do research on traffic data and mapbox
- Week 3: watch tutorials to understand the JSON and XML data
- Week 4: write code to draw red dots on the map to show traffic condition and play sounds
- Week 5: Present!

## Completed Work
https://github.com/RuitaoLiang/p-and-e-final-project-spring-2018/blob/master/Screen%20Shot%202018-05-05%20at%205.28.48%20PM.png

https://github.com/RuitaoLiang/p-and-e-final-project-spring-2018/blob/master/Screen%20Shot%202018-05-05%20at%205.29.24%20PM.png

https://github.com/RuitaoLiang/p-and-e-final-project-spring-2018/blob/master/Traffic%20music%20indicator.mov


## References and links

Coding Challenge #57: Mapping Earthquake Data: https://www.youtube.com/watch?v=ZiYdOwOrGyc&t=1643s,
JSON - Introduction: https://www.w3schools.com/js/js_json_intro.asp,
 API Key for Mapbox: https://www.mapbox.com/studio/account/tokens/,
Traffic data API: https://msdn.microsoft.com/en-us/library/hh441726.aspx,
Understand JSON Data: https://www.lynda.com/Web-Development-tutorials/Understand-XML/560344/590554-4.html
