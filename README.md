# Liquid Drug Dispensing Device Using Arduino

## Overview
This project involves designing a liquid drug dispensing device using an Arduino microcontroller. The main functions of the device are to control and monitor the volume of the liquid drug being dispensed, detect air bubbles in the drug, and alert the user when the drug volume is low. The device will display both the pre-set and sensed parameters on an LCD screen. 

## Components
- **Arduino Board**: The central microcontroller used to manage all sensors and control logic.
- **IR Sensor**: Used to detect air bubbles in the liquid drug.
- **Ultrasonic Sensor**: Used to measure the volume of the liquid drug and trigger an alarm when the volume is low.
- **Flow Meter Sensor**: Used to measure the flow rate of the liquid drug.
- **LCD Display**: Used to display the flow rate and the volume of the liquid drug.
- **Buzzer/Alarm**: Used to alert the user when air bubbles are detected or when the drug volume is low.



## Usage
1. **Power On**: Connect the Arduino to a power source.
2. **Initialize**: The device will initialize and display "Flow Rate:" and "Volume:" on the LCD.
3. **Monitoring**: The device will continuously monitor the flow rate, volume, and detect air bubbles.
4. **Alerts**: If air bubbles are detected, the buzzer will sound an alarm. Similarly, if the volume goes below the set threshold, an alarm will be triggered.

## Calibration
- Adjust the `volumeThreshold` and flow rate calculation as per the actual device specifications.
- Ensure all sensors are correctly calibrated and tested before use.


## Troubleshooting
- **No Display on LCD**: Check connections and ensure the LCD is properly initialized.
- **No Alarm Sound**: Verify the buzzer connections and ensure the correct digital pin is used.
- **Incorrect Flow Rate or Volume Readings**: Calibrate the sensors and verify the measurement logic in the code.
