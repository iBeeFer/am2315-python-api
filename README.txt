Copyright 2013 Jörg Ehrsam <joerg@ehrsam.de> / <ehrsam.de>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

http://www.gnu.org/licenses/
-----------------------------------------------------------------
Python Unterstützung für den Temperatur und Feuchtesensor AM2315
am i2c Bus des Raspberry PI
-------------------------------------------------Jörg Ehrsam 2013

Änderungshistorie:
Siehe CHANGELOG.txt

Voraussetzung:
- python3
- quickwire.i2c 
(https://github.com/quick2wire/quick2wire-python-api.git)

Installation:

#tar -xvzf AM2315-x.y.tar.gz
#cd AM2315
#python3 setup.py install 

Example: 
#python3
>>> import AM2315
>>> sensor=AM2315()
>>> sensor.temperature()
24.5
>>> sensor.humidity()
65.3
