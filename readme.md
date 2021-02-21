# Wanhao Duplicator i3 Plus SKR Mini wiring loom

Using Cat6 UTP cable as a wiring loom. Two cables required to provide 16 wires.

## Cable 1 - Extruder stepper and hotend heater

Wire | Purpose | [Board pin](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V2.0/Hardware/BTT%20SKR%20MINI%20E3%20V2.0-PIN.pdf) | Board connector type
----- | ----- | ----- | -----
Blue solid | Hot end heater | HE0 PC8 | Bare wire
Blue stripe | Hot end heater | HE0 12/24V | Bare wire
Brown solid | Hot end heater | HE0 PC8 | Bare wire
Brown stripe | Hot end heater | HE0 12/24V | Bare wire
Green solid | Extruder stepper black | EM 2B | JST 4-pin
Green stripe | Extruder stepper green | EM 1B | JST 4-pin
Orange solid | Extruder stepper red | EM 1A | JST 4-pin
Orange stripe | Extruder stepper blue | EM 2A | JST 4-pin

## Cable 2 - Fans and sensors

Wire | Purpose | [Board pin](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V2.0/Hardware/BTT%20SKR%20MINI%20E3%20V2.0-PIN.pdf) | Board connector type
----- | ----- | ----- | -----
Blue solid | Cool end fan | FAN0 PC6 | JST 2-pin
Blue stripe | Cool end fan | FAN0 12/24V | JST 2-pin
Brown solid | Part fan | FAN1 PC7 | JST 2-pin
Brown stripe | Part fan | FAN1 12/24V | JST 2-pin
Green solid | Hot end thermistor | TH0 PA0 | JST 2-pin
Green stripe | Hot end thermistor | TH0 GND | JST 2-pin
Orange solid | X endstop | X-STOP PC0 | JST 2-pin
Orange stripe | X endstop | X-STOP GND | JST 2-pin
