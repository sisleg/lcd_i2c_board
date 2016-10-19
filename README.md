A small interface bord used to connect a LCD character or a OLed character
display that uses the classic HD44780 protocol. Via a I2C buss to any microcontroller.

A MCP23017 from Microchip is used. That ccontroller has two 8 bit ports. One is 
used as the databus to the Display. The other port is used for controll lines (3 bits), contoling a backlight or a external led (1 bit). The last four bits is
used for a simple keybord interface.

