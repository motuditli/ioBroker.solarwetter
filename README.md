![Logo](admin/solarwetter.png)
# ioBroker.solarwetter
=================

[![NPM version](http://img.shields.io/npm/v/iobroker.solarwetter.svg)](https://www.npmjs.com/package/iobroker.solarwetter)
[![Downloads](https://img.shields.io/npm/dm/iobroker.solarwetter.svg)](https://www.npmjs.com/package/iobroker.solarwetter)
[![Tests](https://travis-ci.org/ioBroker/ioBroker.solarwetter.svg?branch=master)](https://travis-ci.org/ioBroker/ioBroker.solarwetter)

[![NPM](https://nodei.co/npm/iobroker.solarwetter.png?downloads=true)](https://nodei.co/npm/iobroker.solarwetter/)

## Beschreibung / Description
:de: Dieser Adapter liefert den prognostizierten Solarstrom Tagesertrag für eine bestimmte Region. Die Daten kommen von [http://www.auswahl-plz-bereich.solar-wetter.com](http://solar-wetter.com). 

:uk: This adapter delivers a forecast of the daily amount of solar power for a specific region from supplier [http://www.auswahl-plz-bereich.solar-wetter.com](http://solar-wetter.com). 

## Einstellungen / Configuration
### Region
Örtlichkeit durch Auswahl des Postleitzahlenbereichs bestimmen

Choose your region by selecting from the list of post codes.

![alt text](img/solarwetterSettingScreenshot.jpg "Screenshot Settings")

## Aktivierung / Schedule
Der Adapter startet einmal täglich.

The adapter starts once a day.

##  Datenpunkte / Datapoints

solarwetter.0.forecast.__clearSky__

tvspielfilm.0.forecast.__realSky_min__

tvspielfilm.0.forecast.__realSky_max__

tvspielfilm.0.forecast.__Datum__  (*Timestamp*)



## Changelog

### 0.0.1 (2016-05-12)
* (pix) Adapter created


## License

The MIT License (MIT)

Copyright (c) 2016 pix

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
*Logo is partly crafted by CHALLENGER* :+1: 
