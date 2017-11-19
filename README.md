# Pi_Weather_switchdoc
Simple python code used to interrogate the switchdoc weather board and rack

These are experiments with python on a raspberry pi connected to the Switchdoc Weather Pi Board and their
weather sensor rack.

getwthr.py is the main executable. It uses the sensor drivers provided by Adafruit and Switchdoc to query the sensors and print the results onto the terminal screen.
Additionally getwthr.py creates a JSON like file (wthrdata.dat) that is copied to an Apache web server running on the Pi 
(/var/www/html). 
This file is then used to display weather station data on a web page using the index.html file included in this repository.

See the Wiki for more information.

Much of the code found here is modified versions of code produced by switchdoclabs who has a repository here on github.
