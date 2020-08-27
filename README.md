# DFRobot MQ7 Carbon Monoxide Data Logging
The repo name speaks for itself.  Use this code if you wish to collect MQ7 analog (non-discrete) data and log to CSV files.  Was tested recently and works, at least with an Arduino UNO r3 board.  As specified and necessitated by the sensor, external calibration is required for absolute accuracy.

Collates code from [FeifeiDeakin/MotionDataLogging: MotionDataLogging](https://github.com/FeifeiDeakin/MotionDataLogging), [Carbon_Monoxide_Gas_Sensor_MQ7___SKU_SEN0132_](https://wiki.dfrobot.com/Carbon_Monoxide_Gas_Sensor_MQ7___SKU_SEN0132_), [Code Walkthrough | Adafruit Data Logger Shield | Adafruit Learning System](https://learn.adafruit.com/adafruit-data-logger-shield/using-the-real-time-clock-3) and [adafruit/Light-and-Temp-logger](https://github.com/adafruit/Light-and-Temp-logger).

Licensed under GNU LGPL as necessitated by [DFRobot](https://www.dfrobot.com/) (see [this page](https://www.gnu.org/licenses/) for more info).

## Usage:
It is very simple to use and implement: If you purchase an arduino board, all you have to do is just [download](https://www.arduino.cc/en/main/software) the Arduino integrated development environment (IDE), clone or release-download the code, import it into the Arduino IDE as a new sketch, connect the Arduino board over USB, press Control+R to verify and compile the code, then finally press Control+U to transfer / upload the compiled program to the board.  Should work straight out of the box.

Use at your own risk! :) Though you can't and shouldn't go wrong with this one.