# S-House
## Project description
The goal of the project is to create a smart house where we can monitor and control the electronic devices of the house remotely. To do that we will use different devices and tools:

- **Sensors**: We will use simple sensors designed for arduino based projects, but they will work just fine with our project. We can also add in the futur more developped sensor.
- **ESP32 board**: This ESP32 board will be responsible of receiving and processing the data from the different sensors connected to it, then send the processed data to a gateway
- **Arduino**: Wa can also use it like the ESP32 board to connect more sensors (if the ESP32 cannot connect to any more sensors)
- **RaspberryPi (Gateway)**: The RaspberryPi will act as a gateway between the sensors (edge devices) and the internet network

For data visualisation on the phone or on the conputer, we can use the existing web and mobile application, but in the futur we can create our own application and add it to our project.

## ESP32 board

The board used in this project is a 