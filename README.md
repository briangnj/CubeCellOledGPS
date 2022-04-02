# CubeCell_OLED_GPS
Arduino sketch for Heltec CubeCell to display GPS info via OLED Display

This script has been tested with the Heltec Cubecell HTCC-AB02S v1.1 board and is a modified version of the example that comes with the Heltec libraries. 

Changes from the original:
Using SDA/SCL instead of I2C interface for display driver

Using the older Air530Class GPS module instead of Air530ZClass as the satellite reception is better. 
