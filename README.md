# ESP32-e-Paper-Weather-Display
An ESP32 and an ePaper Display reads Open Weather Map and displays the weather

Go to Sketch > Include Library... > Manage Libraries.... Then, for each library, put its name into the text field to have its metadata pulled from the internet and displayed below. Select the latest version and install it. Make sure to come back to this dialog from time to time to keep each library up to date. Also make sure that you only have one version of each of the libraries installed.

- 'Mini Grafx' by Daniel Eichhorn
- 'ESP8266 WeatherStation' by Daniel Eichhorn (required for additional fonts)
- 'Arduino JSON' v6 or above
-  Adafruit_GFX
-  GxEPD2

Download the software and install all 3 files in the same sketch folder.

1. - ESP32_OWM_Current_Forecast_29_epaper_vX always choose the latest version
   - ESP32_OWM_Current_Forecast_42_epaper_vX always choose the latest version (This version requires *** Arduino JSON v5.13.2 ***)
   - ESP32_OWM_Current_Forecast_75_epaper_vX always choose the latest version
   - ESP32_OWM_Current_Forecast_75_epaper_v10 now requires GxEPD22 library 
   

2. owm_credentials.h

3. ArialRounded.h
   epaper_fonts.h (for v10 onwards)

Obtain your OWM API key - it's free

4. Edit the owm_credentials.h file in the IDE (TAB at top of IDE) and change your Language, Country, choose your units Metric or Imperial and be sure to find a valid weather station location on OpenWeatherMap, if your display has all blank values your location does not exist!.

Go to Sketch > Include Library... > Manage Libraries.... Then, for each library, put its name into the text field to have its metadata 

NOTE: See schematic for the wiring diagram, all displays are wired the same, so wire a 7.5" the same as a 1.54" or 2.9" display!

Compile and upload the code - Enjoy!

![alt text](https://github.com/G6EJD/ESP32-e-Paper-Weather-Display/blob/master/IMG_2096b.jpg)

