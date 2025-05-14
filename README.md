# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32 Introduction

## Purpose
Set up ESP32 and Arduino enviornment. Perform Blink function
## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Video 1: 

##### Other Links: 
https://lastminuteengineers.com/getting-started-with-esp32-cam/

## Steps I followed
1. connect the ESP32-CAM to your computer using a USB cable. Then, navigate to Tools > Port and choose the COM port to which the ESP32-CAM is connected.
2. After installing the ESP32 Arduino Core, restart your Arduino IDE and navigate to Tools > Board > ESP32 Arduino and select AI-Thinker ESP32-CAM.
3. Rewrite didgitalwrite script to correspond led 4 pin
4. compile sketch to light up the led light.

## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

1.esp32 camweb server did not connect to internet. Attempted several times. Possibily wifi name was entered incorrectly

 How did I solve: esp32 webserver
 1. Made personal hotspt open to personal laptop and connected to iPhone network. Found ip address to connect to 
 2. Attempted hard esp32 reset
### Example Problem
1. Arduino code will not load on ESP32 Cam.
   Answer: Camera drivers were incorrect I needed to install the driver: [https://www.wch-ic.com/downloads/CH341SER_ZIP.html](https://github.com/martin-ger/esp32_nat_router).  I used file, "CH341SER.ZIP" and it worked.
   2.chatgpt
   3.google


## Final Report
