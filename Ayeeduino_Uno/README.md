# Ayeeduino Uno
## With CH340G for serial communication

</p>This is a custom Arduino type development board that houses the AtMega328p and can be programmed using the Arduino IDE. In order to succesfully program the board, first you need to flash the bootloader on the MCUs using either the Arduino IDE or Nick Gammons Bootloader Programmer:</p>
https://www.gammon.com.au/bootloader<br>

</p>The gerber files can be sent to JLCPCB.com for manufacturing since they agree with their constraints and the components can be ordered via LCSC.com using the BOM provided.<br>
Soldering this PCB may come across as a bit of a challenge for some since it requires soldering a 32 pin TQFP package as well as 3225 packaged crystal oscillators with pads on the bottom. Both of these are easily solderable if you have access to a hot air station, but definitely doable with a temperature controlled iron and a well tip.<br>
The BOM can be simply uploaded to LCSC using their BOM tool to add all required components directly to cart. Note to be made here, header pins are not included in the BOM since I want to leave the choice of male/female up to the designer.</p>
&nbsp;&nbsp;&nbsp;&nbsp;Goals:
 <il>   

- Reduce the physical size of the Arduino Uno by roughly half.
- Implement USB-C for future proofing.
- Remove unnecessary components.
 <il>
