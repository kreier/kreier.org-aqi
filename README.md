# kreier.org/aqi

This website is a public frontend for aqi measurements at the American International School Vietnam.

### Design

It is intendet to maximize the available space on the display and using responsive design and html5 it should indicate the important data both on smartphones, laptops and PCs.

### Data

The first measurement station is an ESP8266 with a NOVA SDS011 dust sensor for PM2.5 and PM10 and a DHT22 for humidity and temperature. It's located in a shadow area outside on the AIS area in Nha Be, Ho Chi Minh City. The DIY instructions to build this sensor can be found at [luftdaten.info](https://luftdaten.info/en/home-en/). The firmware for the ESP8266 is provided as well.

The second measurement is taken by a [Netatmo](https://netatmo.com) weather station. It measures temperature, humidity and the barometric pressure. With the connected rain sensor we get some valuable data for the rain season as well. The two inside modules measure temperature, humidity and CO2 concentration in the server room and in the school room 407B. You can check our present and historic measurements with the [iOS App](https://itunes.apple.com/us/app/netatmo-weather/id532538499) or [Google Play App](https://play.google.com/store/apps/details?id=com.netatmo.netatmo) with login <b>netatmo@kreier.org</b> and <b>ais1234!</b> as values.

The third measurement is with the same station as #1, but at the 8th floor outside at the Park Residence in Nha Be. The distance to AIS is 6.5 kilometers as the crow flies. Since both stations are outside of Saigon the results should be comparible.

The fourth measurement is taken from official sources (will be updated later).

Recent measurements can be seen at https://kreier.org/aqi .
