Template library for reading SDM220/SDM120 Modbus Energy meter.

Reading via Software Serial library (https://github.com/plerup/espsoftwareserial)<br>
and rs232<->rs485 converter with automatic flow direction control (look at hardware_sdm220.jpg)<br>
(Not work with simple max485-only converters because this lib does not control max485 DE/RE lines)


Tested on wemos d1 mini->ESP8266 with Arduino 1.6.9 & 2.3.0 esp8266 core

crc calculation by Jaime García (https://github.com/peninquen/Modbus-Energy-Monitor-Arduino/)

2016 Reaper7