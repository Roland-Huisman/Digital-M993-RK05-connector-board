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




Copyright 2019 Roland Huisman

Permission is hereby granted, free of charge, to any person obtaining a copy of this project and associated documentation files , to deal in the project without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the project, and to permit persons to whom the project is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the project.

THE PROJECT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE PROJECT OR THE USE OR OTHER DEALINGS IN THE PROJECT.
