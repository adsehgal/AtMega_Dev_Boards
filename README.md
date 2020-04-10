# Custom AtMega Development Boards
### Aditya Sehgal

</p>This repo is a compilation of custom development boards I have taken upon myself to design. These boards house the AtMega family of microcontrollers and are similar to Arduino boards, however, with personal customizations as follows:</p>
 <il>   

- Reduce the physical size of the reference Arduinos by roughly half.
- Implement USB-C for future proofing.
- Remove unnecessary components.
 <il>
<br>

</p>The gerber files can be sent to JLCPCB.com for manufacturing since they agree with their constraints and the components can be ordered via LCSC.com using the BOMs provided.<br>
Hand soldering the PCBs may come across as a bit of a challenge for some since it requires parctice with QFP packages as well as 3225 packaged crystal oscillators with pads on the bottom. Both of these are easily solderable if you have access to a hot air station, but definitely doable with a temperature controlled iron and a well tip.<br>
The BOMs can be simply uploaded to LCSC using their BOM tool to add all required components directly to cart. Note to be made here, header pins are not included in the BOM since I want to leave the choice of male/female up to the designer.</p>