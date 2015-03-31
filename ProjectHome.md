ArduLog is a stamp size circuit which has the  capability of doing RS232, I2C and Analog logging.

It's including a microSD socket, 2 color led for status and 4 input pin that connected with 6 ports of Atmega328 processor.

We are using it for recording the GPS positions from directly any GPS embedded device.
It is supporting all GPS models which have standard GPGGA NMEA protocol.

The Baudrate of ArduLog is configurable with putting the _BAUD.TXT file into the root folder of microSD card.  We tested it with all rates between 4800-115200baud._


The PCB is compatible with "Arduino Pro 16Mhz" BootLoader and firmware upgradeable with Arduino Compiler.
