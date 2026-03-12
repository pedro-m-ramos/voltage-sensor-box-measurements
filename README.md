# voltage-sensor-box-measurements
The sensor-box is based on an LEM LV 25-P Hall-effect voltage sensor, configured for operation in the European nominal 230 V RMS power grid voltage. 
The sensor input voltage was supplied by a Wavetek 9100 calibrator. 
To avoid interferences with the 50 Hz power grid, the AC source frequency was set to 60 Hz. 
The sensor-box input voltage was measured with an Agilent 34410A  6.5-digital multimeter operating as voltmeter - this setup enables the use of the measurements from the multimeter or from the calibrator to assess the uncertainties of the sensor-box input.
An Agilent 3458A 8.5-digit multimeter, also operating as voltmeter, measured the sensor-box output voltage. 


## How to Use
The data is stored in the text file, where each line corresponds to a different sensor-box input voltage, from 4 V to 300 V with steps of 25 mV.

The columns, in the following order, present the data:
1. Input Voltage [V] from the Wavetek 9100 calibrator (with 8 decimal places)
2. Input Voltage [V] from the Agilent 34410A voltmeter (with 8 decimal places)
3. Output Voltage [V] from the Agilent 3485A (in scientific notation with 7 significant digits)
4. Maximum Error [V] of the Wavetek 9100 calibrator, for the measured input voltage (in scientific notation with 7 significant digits)
5. Maximum Error [V] of the Agilent 34410A voltmeter, for the measured input voltage (in scientific notation with 7 significant digits)
6. Maximum Error [V] of the Agilent 3485A voltmeter, for the measured output voltage (in scientific notation with 7 significant digits)
