# [PSU Replacement](/TI994A_PSU_Replacement)
A fork of a fork.  <br>
Created a version using KiCad 9, with rounded corners and more information to make the build more "idiot proof".<br>

Replaces the 99/4A's original 18VAC/7.5VAC power supply with a regulated 12VDC supply.  The board then generates the required ±5VDC voltages using a DC-DC buck converter (+5VDC) and switching regulator (-5VDC).  The +12VDC comes directly from the external power supply.<br>

## Main Parts
- DFRobot DFR0831 DC-DC Buck Converter (+5VDC supply)
- Recom R-78CK5.0-0.5 Switching Regulator (-5VDC supply)
- Vishay SUP53P06-20 MOSFET (protects against reverse polarity DC input)

## Original Designs
- [Johnny Blanchard's original](https://codeberg.org/Jonn-reenthused/TI99-4A-dc-power-board)
- [dabone's fork](https://github.com/dabonetn/ti99psu-replacement)

## Status
- 2-Nov-2025: Designed, not yet fabbed & tested

