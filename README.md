
# Description

This is a clone from [etrombly's rfm 69 library](https://github.com/etrombly/RFM69) adapting it to python3.
I explicitely also had to control the NSS pin on the RPI4 (not sure why).

# Hardware setup

Attach the RFM69 as follows:

| RFM pin | Pi pin  
| ------- |-------
| 3v3     | 17  
| DIO0    | 18 (GPIO24)  
| MOSI    | 19  
| MISO    | 21  
| CLK     | 23  
| NSS     | 24  
| Ground  | 25  
| RESET   | 29
