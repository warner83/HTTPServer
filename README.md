# HTTPServer
HTTP Server wit Micro Phython (v1.3.8-43-gc114496) an CC3000WiFi (Adafruit)

wiering
-------

```
C3K pin | board pin
--------+----------
GND     |    GND
Vin     |    Vin
IRG     |    Y3
V3EN    |    Y4
CS      |    Y5
CLK     |    Y6
MISO    |    Y7
MOSI    |    Y8
```


using
-----
add the password in inic3k.py

per PnTTY (Win7)
```
import inic3k
inic3k.ini()

import httpserver
httpserver.ini('',80)
```
