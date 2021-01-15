# DIY-VAN-CONTROL
Build a Raspberry-Pi/node-Red Van Control System. 


This system is based on Node-Red, so it can be used on different platforms. 
It will have a modulare flow system. Each flow provid a seperate function. 

is working: 
- Nextion Display
- DS18b20
- Webasto - W-bus integration. 


Quick Start. - Self install
1. Install Node.js & Node-red
2. Import the MainFlow
3. Setup your ports. Setup your modules.
4. Import the flows
5. Toggle all Flows you don´t use to inactive
6. install the used nodes:
  - node-red-contrib-ads1x15
  - node-red-contrib-binary
  - node-red-contrib-ds18b20-sensor
  - ncd-red-comm 
  
  
  
  
Quick Start - Use Ready Image: 
- burn our image to sd - recommend Win32 Disk Imager
- put it in your raspberry and you are ready
- connect to wifi pekawayDIYcontrol - pw: pekawayYES
- dashboard: http://peka.way
- Node-red config board - http://192.168.4.1:1880

Image: http://pekaway.de/pekaway_control.zip
- version 0.0.2



next: 
- china diesel heater protocol integration
- easy connect pcb, with waveshare 8 relais pcb
- raspberry pi hat pcb
- peacefair rs485 shunt
- daly/heyo BMS integration



All 3d parts:
https://github.com/pekaway/3d-parts
  

  


