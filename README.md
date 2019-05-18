# Digital-M993-RK05-connector-board

This is a replacement board for the Digital M993 cable PCB. I've found two versions of the board which I combined in one board. So you can built the board in two ways. 

1: You can place R2 and leave out Q1, R1, D1 and U1.

Or

2: You can place Q1, R1, D1 and U1 and leave out R2.

I think DEC had some problems driving this signal at a certain amount drives.
Jumper wires R3 and R4 are there because in one board J2-A was
connected to AU1 and at another board it was connected to AU2.

Use 90 degree connectors for J1 and J2 because of the limitid space in the drive!

D1: 1n748a, 3,9 Volt zener diode
R1: 470 Ohm
Q1: BC557
R2,3,4: 0 Ohm resistor or wire
J1, J2: XG4A-4034 (90 degree 40 pin connector)
