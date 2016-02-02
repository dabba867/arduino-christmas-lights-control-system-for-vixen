NOTE: For some reason Google has decided not to support downloads from projects here any longer so you can find the project downloads at: https://drive.google.com/folderview?id=0Bze2HXmQBR8CSU9NMWZSNlFUdFk&usp=sharing

```
The code supporting the hardware for a xmas lights control system powered by an Arduino Mega.

Videos for Version 2 of the controller can be found at this URL:
https://www.youtube.com/watch?v=ozCosT5Ki_Y&list=PLp21wF8e4XnjCTjyARowU-Qdw3qkuTACi

Version 2 uses:
1 - Arduino Mega 2560
4 - SainSmart SSR 8 channel boards
1 - Vixen 2.5.0.8 software package
32 - electrical outlets
1 - FT232R breakout board
32 - 3mm LEDs
1 - 12V/20mA 4mm Green LED with Holder
32 - 1k resistors
32 - random cross SSRs, G3MC-202PL-DC5 (these replace the zero-cross SSRs that come on the SainSmart boards)
1 - H11AA1 DIP forthe zero-cross detection (driving the interrupts on the Arduino)
1 - 5v Enercell 5V/3.6 Amp AC Adapter with USB
A boat load of ribbon cabel and 14 guage electrical wire.
1 - Whole House FM Transmitter http://www.amazon.com/Whole-House-FM-Transmitter-2-0/dp/B003FNQHOW/ref=sr_1_1?ie=UTF8&qid=136457053&sr=8-1&keywords=Whole+House+FM+Transmitter+2.0

---------------------------------------------------------

Videos for Version 1 of the controller can be found at this URL:
http://www.youtube.com/watch?v=B5Wsovc2TSg&list=PLp21wF8e4XnjNSQHJcnvNSDdb1wsPOfHi 

Version 1 used:
1 - Arduino Mega 2560
1 - SainSmart 16-Channel 12V Relay Module
1 - Vixen 2.5.0.8 software package
16 - electrical outlets
1 - FT232R breakout board
16 - 3mm LEDs
16 - 1k resistors
1 - 32v HP power supply
A boat load of ribbon cabel and 14 guage electrical wire.

It attempted to use the PWM pins on the Arduino to do dimming. 
The relays were mechanical not solid state so this didn't work. 
It was REALLY noisy and the dimming was more or less just a 
flashing effect.
```