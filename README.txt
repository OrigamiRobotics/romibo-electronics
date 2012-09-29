README.txt
September 28, 2012

This folder contains the CAD (Computer Aided Design) files for the Romibo (R)
robot Revision 3 controller circuit board.  These design files were created by
Garth Zeglin using the commercial CAD program EAGLE 5.10.0.  The controller is a
"shield" which fits a standard Arduino Mega microcontroller.  The board design
includes all I/O for the Romibo robot.  User-friendly documentation is located
separately in the romibo-documentation package.

All files are available under the terms of the GNU General Public License
Version 2, the text of which appears in GNU-General-Public-License-Version-2.txt.

The notice for all such files is as follows:

    Copyright (C) 2012 Origami Robotics LLC.

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

Note that this license is applied under the theory that a CAD file is "source
code" which is compiled into "object code" in the form of a plot file, drawing,
or fabricated object.  In particular, if you distribute any changes to the
design, you must also include any changes to CAD files.  This note does not
supersede any terms of the license.

The Romibo(R) name is trademarked by Origami Robotics, LLC, and is not itself
available under this license.

================================================================
Description of files:

EAGLE design rules	Advanced-Circuits-design-rules.dru
EAGLE CAM definitions	Advanced-Circuits.cam
full license text	GNU-General-Public-License-Version-2.txt
github metadata		README.md
this file		README.txt
special pin functions	Romibo-Arduino-Pin-Assignments.xls
parts list		Romibo-Shield-Component-List.xls
external wiring table	Romibo-Wiring-Harness.xls
EAGLE parts library	Romibo.lbr
EAGLE board layout	RomiboShield.brd
EAGLE circuit schematic	RomiboShield.sch

top copper Gerber plot	board-fabrication/RomiboShieldRev3.cmp
top silkscreen plot	board-fabrication/RomiboShieldRev3.plc
bottom silkscreen plot	board-fabrication/RomiboShieldRev3.pls
bottom copper Gerber	board-fabrication/RomiboShieldRev3.sol
top solder mask plot	board-fabrication/RomiboShieldRev3.stc
bottom solder mask plot	board-fabrication/RomiboShieldRev3.sts
Excellon drill program	board-fabrication/RomiboShieldRev3.xln

================================================================
