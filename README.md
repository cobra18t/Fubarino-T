fubarino: Social Hardware and Software
========
Main Project Pages are:
http://fubarino.org

The Fubarino SD board brings affordable, breadboard compatible high speed computing power to the Arduino-compatible chipKIT/MPIDE platform. It is able to run almost all Arduino sketches right out of the box at a great price, and includes more memory, speed, and I/O pins than a typical Arduino or clone. And it includes a microSD card slot for easy sketch access to huge file storage.

cobra18t's FubarinoSDt (still in beta testing, files will be added soon)
======
This is an edited version of Brian Schmalz's original FubarinoSD. The main changes are as follows:
* Used the PIC32MX440F512, which has 512k flash memory, versus the normal 256k.
* Used a different SD socket and brought the Card Detect out to a change notification pin (A14)
* Used a 800mA regulator for just a little more *umph*
* Used Sparkfun's locking headers so breadboarding does not necessarily require soldering
* Minor layout changes to adhere to my board fabricators design rules
* Changed packages for crystal and diodes for cost reasons
* Blue LED on pin 21...you gotta love the blue!

FubarinoSD
======
Class on a stick. Course materials can fit on the SD card. The device mounts as a USB device. Unfortunatley, at 1.0 speeds. But 
it wll cut 45 minutes of getting started to 15 minutes. When offering online course using electronics, all the course materials can be placed on the board.



The goal with the project is two have two boards that are excellent for small, and bread boardable projects.

Social Hardware:
=====
* Open Source
* Open Hardware
* Sharable


Licensing
====
The Fubarino SD hardware is licenced under the Solderpad Hardware License v0.5. All MPIDE source code is licenced under GPL or other open source software licenses.

Availability:
========
These boards are Open Hardware and all the files are management in this project, and are licensed as OpenSource.
They can be created from the Eagle files right away or purchased at [Seeed Studio](http://www.seeedstudio.com/depot/fubarino-sd-p-1265.html?cPath=132_133).


