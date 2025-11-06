# [PSU Replacement](/TI994A_PSU_Replacement)
A fork of a fork.  <br>
Created a version using KiCad 9, with rounded corners and more information to make the build more "idiot proof".<br>

![3D view](/TI994A_PSU_Replacement/TI_994A_PSU_Replacement_3D.png)

Replaces the 99/4A's original dual-voltage 18VAC/7.5VAC power supply with a regulated 12VDC supply.  The board then generates the required ±5VDC voltages using a DC-DC buck converter (+5VDC) and switching regulator (-5VDC).  The +12VDC comes directly from the external power supply.<br>

## Main Parts
- DFRobot DFR0831 DC-DC Buck Converter (+5VDC supply)
- Recom R-78CK5.0-0.5 Switching Regulator (-5VDC supply)
- Vishay SUP53P06-20 MOSFET (protects against reverse polarity DC input)
- G-Switch SS-22G88-G090 DPDT switch (need to trim a little)

## Original Designs
- [Johnny Blanchard's original](https://codeberg.org/Jonn-reenthused/TI99-4A-dc-power-board)
- [dabone's fork](https://github.com/dabonetn/ti99psu-replacement)

## Status
- 2-Nov-2025: Designed, not yet fabbed & tested, need to double-check switch position

# [Joystick Adaptor](/JoystickAdaptor)
Wanted to design my own joystick adaptor, so I did.

![3D front view](/JoystickAdaptor/TI_994A_Joystick_Adaptor_Front_3D.png)
![3D back view](/JoystickAdaptor/TI_994A_Joystick_Adaptor_Back_3D.png)
