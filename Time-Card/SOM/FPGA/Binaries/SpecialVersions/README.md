# Special Bitstream Versions

TimeCardDoublePPS.bit
ANT4 --> PPS Output from PPS Master
ANT3 --> TimePule from GPS Module (which goes to the PPS Slave)

TimeCardTopUSBUARTGPS.bit
The USB Uart (used for the UCM) is directly mapped to the GPS Module UART.
Flashing this version allows to connect e.g. via u-center. With this bitstream the UCM can't be used.