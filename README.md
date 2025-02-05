** Description
LiPo Power Board is a power manager for your battery-powered product. Since the breakout format, it is intended for prototyping and development. It is designed for a single cell LiPo battery (3.7V) and to supply 2 voltages: a fixed 3.3V and a secondary adjustable output, able to deliver higher voltage and current. A physical switch allows you to cut out the voltage on both channels. USB-C and Jack connectors allow to recharge the battery.

The boost part is very flexible since you can just change the ratio between 2 resistors to change the voltage output. Moreover you can copy and paste it to get a third voltage output.

A typical application in which this board finds a perfect suit is where the MCU runs at 3.3V and sensors and actuators (such as LEDs WS2812B) requires higher and stable voltage.

** Features
leakage current 3.81mm; 3D model; min output guarantee current at 5V (tested@3.3V): >400mA
3.0.0 ✅: MCP73837 MSOC -> DFN (thermal issue); Board shape (mounting holes); LEDs moved; NOTE for assembling: orientation marking of chip U1 is its ID
Notes about versions
EasyEDA doesn't let you switch among releases unless you have complete access to the project. If you have questions about old versions, drop me a message.
The real max charge current of versions 1.x and 2.x can be lower than programmer due to thermal limitation of MSOP version. If you really care about charge speed, you should look at DFN version, which has a thermal pad that improves heat dissipation. The max current may also be limited by the protection circuit of your battery.
** Versioning conventions
Each printed board has a version. Version advancements are ruled accordingly to Semantic Versioning.

To show the status of each version I use the following symbols:

A White Heavy Check Mark (✅) means that it is successfully tested;
A Negative Squared Cross Mark (❎) means that it was almost successfully tested (the main functionalities are fine), but there are bugs affecting minor funcionalities;
A Warning Sign (⚠) means that the board is not usable out of the box but the bugs are fixable in DIY (decent) fashion;
A Cross Mark (❌) means that there are some problems that makes it unusable;
A White Question Mark Ornament (❔) means not tested.
** Additional References
Application note AN1149 by Microchip, Designing A Li-Ion Battery Charger and Load Sharing System With Microchip’s Stand-Alone Li-Ion Battery Charge Management Controller. A useful introduction to implement a proper battery manager.
