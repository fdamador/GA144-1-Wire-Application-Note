GA144-1-Wire-Application-Note
=============================
This document describes a method to interface the Dallas Semiconductor high-precision one-wire digital thermometer (DS18S20) device with the EVB001 evaluation board. The hardware and software interface, discussed in this app note, uses arrayFORTH and polyFORTH, respectively. This illustrates one way to prototype such an interface from the manufacturer's one-wire protocol documentation.

The one-wire kernel only uses 1 of 144 nodes for sending and receiving bytes over the one-wire network. The code does not include CRC error checking, but could be added at a later time for real applications. This applications note shows the basic bare-bone mechanisms needed to both interface and communicate via one-wire bus.

This effort was possible through Brad Rodriguez’s one-wire high level Forth implementation on CamelForth with GNU GPL v3 license; however, the one-wire library is now release under the BSD 3-Clause license with a small optional donation for its use.

Licensing
=========
arrayFORTH’s one-wire kernel and polyFORTH’s interface to the arrayFORTH’s one-wire kernel, for the GreenArray’s F18A computer, by Franklin Amador is licensed under a Creative Commons Attribution-ShareAlike 4.0 International.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">one-wire Kernel</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Franklin Amador</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
