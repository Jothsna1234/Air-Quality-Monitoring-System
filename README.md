# Air-Quality-Monitoring-System



 * Air Quality Monitor with LCD Display 🌬️📊
This Arduino project measures air quality using an analog sensor and displays the Air Quality Index (AQI) on an LCD display. 
It categorizes air quality into four levels: Fresh Air, Good, Bad, and Harmful, based on predefined thresholds.

* Components Used 🛠️
Arduino board (e.g., Arduino Uno)
Analog air quality sensor
I2C LCD display module
Jumper wires



* Installation ⚙️
Connect the analog air quality sensor to the Arduino board.
Connect the I2C LCD display module to the Arduino board using the Wire library.
Upload the provided Arduino code to the Arduino board using the Arduino IDE or compatible software.



* Usage 🚀
Power on the Arduino board.
The analog air quality sensor measures the air quality and sends the data to the Arduino.
The Arduino code categorizes the air quality based on predefined thresholds:
Fresh Air (AQI <= 400)
Good (400 < AQI < 750)
Bad (750 <= AQI < 1200)
Harmful (AQI >= 1200)
The categorized air quality information is displayed on the LCD screen, along with the measured AQI value.
The process repeats continuously, providing real-time air quality monitoring.


* Circuit Diagram 📝

* Note 📝
Adjust the thresholds in the Arduino code according to the specifications of the air quality sensor and desired sensitivity.
Ensure proper calibration of the air quality sensor for accurate measurements.
