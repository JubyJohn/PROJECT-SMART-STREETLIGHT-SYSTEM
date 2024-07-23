# PROJECT-SMART-STREETLIGHT-SYSTEM


## AIM
To create a streetlight system using LDR interfaced with Arduino.


## COMPONENTS

<br> 1) Arduino UNO R3
<br> 2) LDR Sensor Module
<br> 3) USB Cable
<br> 4) Jumper Wire


## CONNECTION

### LDR Sensor Module Pin Diagram

 ![LDR-Sensor-Module](https://github.com/user-attachments/assets/2694e247-3e81-47c2-bff5-eaa2b9c23067)

<br> S  = Output     ---->  A0
<br> Middle    = power supply  ---->  5V
<br> GND   = ground   ---->  GND


## PROCEDURE

<br> Step 1 : Interface Arduino board to Arduino IDE using port.
<br> Step 2 : Interface Arduino board with LDR and print analog values on serial monitor.
<br> Step 3 : Modify the program to get desired outputs.


## OUTPUT

 ![LDR_W_Arduino](https://github.com/user-attachments/assets/fc095166-11c9-4d61-ad64-8088bfd7368e)

<br> On serial monitor , when done uploading
<br> DAY TIME - LIGHTS OFF    // when light is detected by LDR, LED turned OFF
<br> NIGHT TIME - LIGHTS ON  // when no light is detected by LDR, LED turned ON
