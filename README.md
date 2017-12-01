# Pi_Weather_switchdoc
Simple python code used to control a Raspberry Pi to interrogate a switchdoc weather board and rack

The project uses Python on a Raspberry pi connected to the Switchdoc Weather Pi Board and a switchdoc
weather sensor rack.

Weather information is displayed to a user through a web page sitting in an Apache server on the Raspberry Pi.

getwthr.py is the main executable. It uses the sensor libraries provided by Adafruit and Switchdoc to query the sensors and print the results onto the terminal screen.
Additionally getwthr.py creates a JSON like file (wthrdata.dat) that is copied to an Apache web server running on the Pi 
(/var/www/html). 
This file is then used to display weather station data on a web page using the index.html file included in this repository.

See the Wiki for more information.

Much of the code found here are modified versions of code produced by switchdoclabs who has a repository here on github.
I would like to thank Adafruit (adafruit.com) and Switchdoc labs (switchdoc.com) for their contributions to the open source community. We all benefit when people share. 
