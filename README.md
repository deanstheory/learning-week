# micropython-esp32

<img src="assets/micropython-esp32.png">

This notebook introduces MicroPython running on ESP32 based microcontrollers. 

Jupyter Notebook running a MicroPython Remote kernel is used to interact with an ESP32 microcontroller over its REPL interface. An overview of the ESP32 hardware and associated MicroPython libraries is presented. 

MicroPython sample code presented include:
- Control of a LED from GPIO pins.
  - Hardware timers.
  - Pulse Width Modulation (PWM).
  - Triggering a LED from a hardware interrupt.
  - Capacitive touch.
- I<sup>2</sup>C bus
  - I<sup>2</sup>C bus scan.
  - BME280 sensor control.
  - Inertial Measurement Unit.
- Introduction to ESP32 Wifi.
  - Wifi network scan and connection.
  - Set RTC from NTP server.
  - HTTP requests.
- Concurrent programming model using AsyncIO.
- ESP32 deep sleep.
- Upload scripts to the microcontroller.
- Sigrok PulseView and logic analyzers.

