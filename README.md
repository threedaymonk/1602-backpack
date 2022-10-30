# 1602 Backpack

![Board attached to 16-2 display](./1602-backpack.jpg)

A small backpack board to add any or all of the following to a 1602 LCD display
(and other variants with similar pinouts, like 2004):

- contrast adjustment pot
- supply backlight from VDD/VSS
- set to write-only mode
- simplify the connection to 8 pins

## How to ...

### Connect to an Arduino or Raspberry Pi with 8 wires

- Solder all three jumpers (Backlight and Write only)
- Solder a header to the short 8-pin connector
- Install a 10K trimmer

### Add contrast adjustment to a device without it (e.g. Kawai K1r)

- Install a 10K trimmer
- Remove the third pin (VO) from a 1x14 header and solder it onto the first
  14 pins (rightmost when looking from behind).
