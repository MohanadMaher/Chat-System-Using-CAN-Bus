# Chat-System-Using-CAN-Bus

Implemented a chatting system between two MCUs (TM4C123). The messages are transmitted as 8-Bytes message over CAN bus with a message maximum size of 200 Bytes. Using UART, the message is then presented to the user.

The project is implemenetd on Tiva C (TM4C123GH6PM).

Used Components: 
- 2 Tiva Cs
- 2 CAN transceivers (mcp2551)
- 10 K OHM resistors
- Jumpers
- BreadBoard

The image below shows the state flow of the system.

![image](https://user-images.githubusercontent.com/89541126/163736220-a74dbea7-6fbc-4f0d-8661-6365d0d791f3.png)
