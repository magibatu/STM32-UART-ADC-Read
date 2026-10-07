
# STM32 ADC to UART Data Acquisition

## Overview
This project is a simple Data Acquisition (DAQ) system built with an STM32 microcontroller. It reads continuous analog voltage values using the hardware ADC and transmits the converted data to a computer via UART. 

## Hardware & Software Used
* **Microcontroller:** STM32F407VGTX
* **IDE:** STM32CubeIDE
* **Library:** STM32 HAL

## Features
* Reads raw analog values from the ADC channel.
* Converts the raw digital data into real voltage values.
* Transmits the processed data over a serial port (UART) for real-time monitoring.

## Pin Configuration
* **ADC Input:** Analog input pin used for reading voltage.
* **UART TX / RX:** Pins configured for serial communication.

## How to Run
1. Clone this repository to your local machine.
2. Open the project folder using **STM32CubeIDE**.
3. Build the project and flash it to your STM32 board.
4. Open a serial terminal program (I used Termite 3.4) on your PC.
