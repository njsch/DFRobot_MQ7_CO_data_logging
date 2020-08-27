# DFRobot MQ7 Carbon Monoxide Data Logging
The repo name speaks for itself.  Use this code if you wish to collect MQ7 analog (non-discrete) data and log to CSV files.  Was tested recently and works, at least with an Arduino UNO r3 board.  As specified and necessitated by the sensor, external calibration is required for absolute accuracy.

Collates code from [FeifeiDeakin/MotionDataLogging: MotionDataLogging](https://github.com/FeifeiDeakin/MotionDataLogging), [Carbon_Monoxide_Gas_Sensor_MQ7___SKU_SEN0132_](https://wiki.dfrobot.com/Carbon_Monoxide_Gas_Sensor_MQ7___SKU_SEN0132_), [Code Walkthrough | Adafruit Data Logger Shield | Adafruit Learning System](https://learn.adafruit.com/adafruit-data-logger-shield/using-the-real-time-clock-3) and [adafruit/Light-and-Temp-logger](https://github.com/adafruit/Light-and-Temp-logger).

Licensed under GNU LGPL as necessitated by [DFRobot](https://www.dfrobot.com/) (see [this page](https://www.gnu.org/licenses/) for more info).

## Usage:
It is relatively simple to use.  If you purchase an arduino board, all you have to do is just:
* [download](https://www.arduino.cc/en/main/software) the Arduino integrated development environment (IDE) for free.
* Clone or release-download the code.
* Import it into the Arduino IDE as a new sketch.
* Use either the [Arduino IDE Library Manager](https://www.arduino.cc/en/guide/libraries) or manually install the following two libraries:
  * The [Adafruit](https://www.adafruit.com/) [Common Sensor Library](https://github.com/adafruit/Adafruit_Sensor); and
  * The Adafruit [Real-time Clock Library (RTCLib)](https://github.com/adafruit/RTClib).
* Connect the Arduino board over USB and make sure that it is registered / assigned to the right COM ports in IDE > tools menu > COM Ports - possibly turn bluetooth off as well.
* Press Control+R to verify and compile the code.
* Finally press Control+U to transfer / upload the compiled program to the board.  Should start working after that - check the upload out and serial moniter.

If you are allergic to graphical interfaces, or are sight-impaired and / or do not have the [Java Access Bridge (JAB)](https://docs.oracle.com/javase/accessbridge/2.0.2/introduction.htm) &ndash; which is quite out-of-date anyway and will probably become increasingly unusable over the years &ndash; then you can always use the [Arduino-CLI](https://www.arduino.cc/pro/cli), the Arduino command-line interface (CLI).  This simplifies the process even more, if you are used to text-based computer interaction.  Also, NVDA is the only screen-reader that reliably works with the IDE, whereas JAWS crashes nearly every single time for some reason.