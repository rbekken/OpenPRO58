OpenPRO58 is an alternative firmware for Eachine PRO58 5.8Ghz Diversity module

It is basicaly ported from RX5808PRO-Diversity project

Major differnecies:

- PRO58 runs on STM32
- There is an external EEPROM memory on I2S( different one than OLED has)
- More buttons (3 on module, 3 additional from goggles)
- Two separated chip selects for RX5808
- Separated signal for switching multiplexers


ToDo
- clean-up EEPROM code - done in very dirty way
- convert soft SPI for modules to hardware
