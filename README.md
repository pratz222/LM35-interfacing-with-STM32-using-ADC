# LM35 Temperature Sensor Interface with STM32

## Project Overview
The LM35 Temperature Sensor Interface project demonstrates how to interface the LM35 temperature sensor with an STM32 microcontroller using the Analog-to-Digital Converter (ADC). This project enables real-time temperature monitoring by reading the analog voltage output from the LM35 and converting it to a digital temperature value.

## Project Motivation
This project was initiated to explore the capabilities of the STM32 microcontroller in reading analog signals and to understand temperature sensing using the LM35 sensor. By implementing this project, I aimed to create a simple and effective temperature monitoring system that can be integrated into various applications.

## Key Features
- **Real-Time Temperature Monitoring:** The system continuously reads the temperature from the LM35 sensor and displays it via UART.
- **Analog-to-Digital Conversion:** Utilizes the STM32's ADC capabilities to convert the analog voltage output from the LM35 into a temperature value.
- **UART Communication:** Sends temperature data to a serial terminal for monitoring.

## Advantages of This System
- **High Accuracy:** The LM35 sensor provides accurate temperature readings, making it suitable for precise applications.
- **Ease of Integration:** The STM32 microcontroller offers a straightforward setup for interfacing with various sensors and devices.
- **Scalability:** This project can be easily expanded to include additional sensors or functionality, such as data logging or remote monitoring.

## Hardware Setup
- **STM32F103C8T6 Microcontroller:** Main controller for managing the ADC and UART operations.
- **LM35 Temperature Sensor:** Connected to the ADC input for temperature measurement.
- **Power Supply:** The LM35 is powered by a +5V supply.

## Components and Libraries Used
- **STM32 HAL Library:** For peripheral initialization and control.
- **UART Communication:** For sending data to a serial terminal.

## Implementation Steps
1. **Hardware Configuration:** Set up the LM35 sensor with the STM32 and connect the appropriate pins for ADC and UART.
2. **STM32CubeIDE Setup:** Configure the project in STM32CubeIDE, generating the necessary initialization code for the ADC and UART.
3. **Code Implementation:** Write the main code for reading temperature values and transmitting them via UART.

## Contribution
Contributions to this project are welcome! If you have suggestions for improvements or enhancements, feel free to open issues or submit pull requests.

## Acknowledgments
Special thanks to the STM32 community and documentation resources that made the development of this project possible.
