# WiFi Modem

![WiFiModem](board/WiFiModem.png)

This is a simple layout for connection a ESP12E to a serial port so that a serial to wireless gateway can be used.  It connects RTS/CTS for flow control (when supported) and has DB9 female and DB25 male connectors.  DB25 male was used to connect directly to an Apple Super Serial Card.  There are jumpers that swap TXD/RXD and RTS/CTS to implement a built-in null modem changer.

There are several types of firmware that could be used on it.

https://github.com/jeelabs/esp-link

ESP Link is a firmware that enables remote access to a microcontroller or serial port through a web page or TCP port.

https://github.com/dhansel/WifiModem

https://github.com/jsalin/esp8266_modem

https://github.com/bozimmerman/Zimodem

https://github.com/maccasoft/WifiModem/blob/master/WifiModem.ino

https://github.com/ssshake/vintage-computer-wifi-modem

https://github.com/stardot/esp8266_modem/wiki

https://github.com/RolandJuno/esp8266_modem    (implements CTS)

