# ESP32-IDF Project with LVGL Framework
This project is built using the ESP32-IDF version 4.4 and the LVGL framework version 8.3. The project is based on esp32_port but has been adjusted to be compatible with LVGL 8.3.

# ESP32-IDF Version
The ESP32-IDF is the official development framework for the ESP32 series of chips, which are highly integrated Wi-Fi + Bluetooth system-on-chips (SoCs) from Espressif Systems. Version 4.4 is the latest stable release of the framework.

# LVGL Framework Version
LVGL is a powerful graphics library for embedded systems that provides a modern, easy-to-use API and a wide range of features. Version 8.3 is the latest stable release of the framework.

# Project Adjustments
This project is based on esp32_port but has been adjusted to be compatible with LVGL 8.3. The adjustments include support for the ILI9488 display driver and the use of lvgl_esp32_drivers as a component for initialization of the LCD and touch panel.

# Example Using ILI9488
An example using the ILI9488 display driver is included in this project to demonstrate the compatibility of the project with this driver.

For Further information check esp32_port example : 
* https://github.com/lvgl/lv_port_esp32
* https://github.com/Mair/learn-lvgl/tree/master/esp32