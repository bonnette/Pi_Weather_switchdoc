# Pi_Weather_switchdoc
A model of python code needed to interogate the switchdoc weather board and rack

The code found here are experiments with python on a raspberry pi connected to the Switchdoc Weather Pi Board and their
weather sensor rack that contains an anomometer, and wind direction sensors.

getwthr.py is the main executable. It uses the drivers to query the sensors and print them onto the terminal screen.
Additionally getwthr.py creates a JSON like file (wthrdata.dat) that is copied to an Apache web server (/var/www/html). 
This file is then used to display weather station data on a web page using the index.html file included in this repository.

Much of the code found here is modified versions of code produced by switchdoclabs who has a repository here on github.
