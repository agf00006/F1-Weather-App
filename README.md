# Assignment 2: Building a Prototype
## Competitive analysis

[Web Page 1](https://raceweather.net/formula-one-weather/) 

This seems to be a basic webpage, displaying the current temperature, precipitation, and wind
speeds at the location of the next F1 race. There are tabs at the top of the page to switch between
racing series as well as drop downs to select different tracks for each series. After inspection, 
there doesn’t seem to be any bootstrap usage, just simple stylesheets and href.
The weather information itself is outsourced from another website called openweathermap.org.  

[Web Page 2](https://www.netweather.tv/weather-forecasts/sports-and-events/f1)

This webpage seems to serve primarily as a weather forecast tool for general use with a search
bar at the top for specific locations. However, there is another section called “sports and events”
that shows weather data for the F1 track of the users choosing. The information presented consists
of weather icons for each hour at the location as well as temp, ground temp, wind, air pressure,
humidity, precipitation, cloud cover, and storm risk.

[Web Page 3](https://www.metcheck.com/HOBBIES/formula1.asp)

This is another very basic webpage that has ads everywhere. There is weather information displayed
for each of the first 14 races immediately on the page. The information displayed is similar to the
previous site, but this one shows the information based on the time each event starts instead of
the current weather. 

While searching for websites similar to my idea, I came across 
just as many reddit threads asking specifically for an F1 weather app or website. 

## GitHub Repository Research

[GitHub Repo 1](https://github.com/Prince-Shivaram/Simple-Weather-App)

This repository features a simple weather application with a search function. The javascript
included in this repository could be useful for implementing a search function as well as for
functions related to displaying the necessary information. There is also an integrated “date builder” 
used to include date and time to the weather information being displayed 

[GitHub Repo 2](https://github.com/LouieOHagan/Simple-Weather-Website?tab=readme-ov-file)

This repository includes an expansive README with details outlining nearly every aspect of the
application and the processes used to create it. Included are design elements and color schemes
that could be useful in my own webpages.The javascript used in this application is also fully commented,
making it easy to understand. 

## Project Description
This application consists of a homepage with a hyperlink to another webpage. The homepage has a
blank space under "Current Forecast" as this will be added later. The homepage also contains a
list of all formula one tire compounds, a feature that will be implemented along with weather
data later. The second page consists of a table containing upcoming formula one races.

## Issues
I was unable to convert from html to cshtml files. I plan to do this later but was unable to
get everything to work correctly with the cshtml files.