# Appliances-Control-with-ESPNOW

![alt text](https://hackster.imgix.net/uploads/attachments/1616108/_6llahv1KHE.blob?auto=compress%2Cformat&w=900&h=675&fit=min)

In the previous two tutorials, we have seen how to get started with ESPNOW and how to transmit DHT11 sensor data via ESPNOW. This tutorial will show how to control physical devices like LED, Relay, or other electrical & electronic applications.

Things that we need:
You need two ESP32 Dev boards, that's all. ESP32 Dev boards have already been equipped with an onboard LED. So, we can just try to control them via ESPNOW. Also, you can add an external LED to the digital pins, and we can control them.

![alt text](https://groupgets-files.s3.amazonaws.com/esp3212/32s-front-s.jpg)

ESP32 is a single 2.4 GHz Wi-Fi and Bluetooth combo chip designed with the TSMC low-power 40 nm technology. It is designed to achieve the best power and RF performance, showing robustness, versatility, and reliability in a wide variety of applications and power scenarios. The ESP32 series of chips includes ESP32-D0WD-V3, ESP32-D0WDR2-V3, ESP32-U4WDH, ESP32-S0WD (NRND), ESP32-D0WDQ6-V3 (NRND), ESP32-D0WD (NRND), and ESP32-D0WDQ6 (NRND), among which,

• ESP32-S0WD (NRND), ESP32-D0WD (NRND), and ESP32-D0WDQ6 (NRND) are based on chip revision
v1 or chip revision v1.1.
• ESP32-D0WD-V3, ESP32-D0WDR2-V3, ESP32-U4WDH, and ESP32-D0WDQ6-V3 (NRND) are based on
chip revision v3.0 or chip revision v3.1.

With low power consumption, ESP32 is an ideal choice for IoT devices in the following areas:
• Smart Home
• Industrial Automation
• Health Care
• Consumer Electronics
• Smart Agriculture
• POS machines
• Service robot
• Audio Devices
• Generic Low-power IoT Sensor Hubs
• Generic Low-power IoT Data Loggers
• Cameras for Video Streaming
• Speech Recognition
• Image Recognition
• SDIO Wi-Fi + Bluetooth Networking Card
• Touch and Proximity Sensing

![alt text](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2020/01/Getting-Started-with-ESP-NOW-ESP32-Arduino-IDE.jpg?fit=1280%2C720&quality=100&strip=all&ssl=1)

ESP-NOW is a wireless communication protocol based on the data-link layer that enables the direct, quick, and low-power control of smart devices without the need for a router. Espressif defines it and can work with Wi-Fi and Bluetooth LE. ESP-NOW provides flexible and low-power data transmission to all interconnected devices. It can also be used as an independent protocol that helps with device provisioning, debugging, and firmware upgrades.

ESP-NOW is a connectionless communication protocol developed by Espressif that features short packet transmission. This protocol enables multiple devices to talk to each other in an easy way. It is a fast communication protocol that can be used to exchange small messages (up to 250 bytes) between ESP32 or ESP8266 boards. ESP-NOW supports the following features: Encrypted and unencrypted unicast communication; Mixed encrypted and unencrypted peer devices; Up to 250-byte payload can be carried; Sending callback function that can be set to inform the application layer of transmission success or failure.

![alt text](https://hackster.imgix.net/uploads/attachments/1544797/pcbway_55Vl7NMRFG.JPG?auto=compress%2Cformat&w=740&h=555&fit=max)

You must check out [PCBWAY](https://www.pcbway.com/) for ordering PCBs online for cheap!

You get 10 good-quality PCBs manufactured and shipped to your doorstep for cheap. You will also get a discount on shipping on your first order. Upload your Gerber files onto PCBWAY to get them manufactured with good quality and quick turnaround time. [PCBWay](https://www.pcbway.com/) now could provide a complete product solution, from design to enclosure production. Check out their online Gerber viewer function. With reward points, you can get free stuff from their gift shop.


