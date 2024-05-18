# java-networking-TCP-UDP-withSerial
This project was produced by the Yıldız Rocket Team software department support team for use in the rocket test system. The components and details used in the project are mentioned below.
## Equipment used:
- Raspberry Pi
- STM32 F446RE
- Connection cable
## Details:
Written in java programming language using IntelliJ IDEA. Socket structure provides communication using TCP/IP and UDP protocols. The client reads the data from the STM32 via serial port, saves the data to a buffer and sends it to the server. The server parses the data from the client with the help of the DataParse class and prints it to a .csv file one after the other. 
