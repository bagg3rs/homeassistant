Sensors and device configuration information

## Gosund UP111/SP111 switch
Use https://github.com/ct-Open-Source/tuya-convert
flash with tasmota
connect to switch and configure wifi
Connect to switch 
- configure > module and choose module type Gosund SP1
- configure other > and enter the below as template
https://templates.blakadder.com/2nice-UP111.html
{"NAME":"2NICE UP111","GPIO":[0,158,0,17,134,132,0,0,131,56,21,0,0],"FLAG":0,"BASE":18}
- give switch static reservation in DHCP and reboot
- Set MQTT options
- In console set SetOption19 1 to enable autodiscovery!

## zigbee2mqtt

## zwave