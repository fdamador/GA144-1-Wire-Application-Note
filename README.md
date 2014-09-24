GA144-1-Wire-Application-Note
=============================
This document describes a method to interface the Dallas Semiconductor high-precision one-wire digital thermometer (DS18S20) device with the EVB001 evaluation board. The hardware and software interface, discussed in this app note, uses arrayFORTH and polyFORTH, respectively. This illustrates one way to prototype such an interface from the manufacturer's one-wire protocol documentation.

The one-wire kernel only uses 1 of 144 nodes for sending and receiving bytes over the one-wire network. The code does not include CRC error checking, but could be added at a later time for real applications. This applications note shows the basic bare-bone mechanisms needed to both interface and communicate via one-wire bus.

This effort was possible through Brad Rodriguez’s one-wire high level Forth implementation on CamelForth [6] with GNU GPL v3 license; however, the one-wire library is now release under the BSD 3-Clause license [10] with a small optional donation for its use.

Licensing
=========
arrayFORTH’s one-wire kernel and polyFORTH’s interface to the arrayFORTH’s one-wire kernel for the GreenArray’s F18A computer. 
Copyright © 2014 by Franklin Amador.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
