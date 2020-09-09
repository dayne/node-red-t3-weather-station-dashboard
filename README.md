# node-red-t3-weather-station-dashboard

(describe it)

##Pre-requisites  

### Hardware 

For this Node-RED dashboard you will need the following hardware components:

- Raspberry Pi
- Acurite 5n1 Sensor
- Acurite Tower Sensor
- RTL Software Defined Radio

### Software

- NodeRED
- rtl_433 software installed

#### Data flow options

Pick a path -- mqtt feed or direct from rtl_sdr tool:

##### mqtt data feed

You can use a data feed from a local or remote MQTT service like setup in [dayne/rtl433_to_mqtt](https://github.com/dayne/rtl433_to_mqtt)

This was done by installing the rtl_mqtt node into Node Red, allowing the data to be directly received and translated into JSON objects which are easier to work with.

##### [node-red-contrib-rtl_433](https://github.com/dayne/node-red-contrib-rtl_433) **recommended**

The other option is to directly read the rtl_433 into your local nodered install:

https://github.com/dayne/node-red-contrib-rtl_433

Having this node enabled the Node Red flow to be installed on any pi without the need for excessive configurations to be done, as long as this node was installed and the necessary hardware was ready.

## Dashboard Installation Steps


## Debugging

## Credits

