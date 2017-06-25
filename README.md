libSML
======

libSML is a library which implements the Smart Message Language (SML) protocol specified by VDE's Forum Netztechnik/Netzbetrieb (FNN).
It can be utilized to communicate to FNN specified Smart Meters or Smart Meter components (EDL/MUC).

### Usage
An example how to use libSML is in the examples directory.

#### Dependencies
openSUSE

	zypper install libuuid1 libuuid-devel

#### Compilation
 
	aclocal
	autoconf
	libtoolize
	automake --add-missing
	./configure
	make
	make install

### License
Copyright 2011 Juri Glass, Mathias Runge, Nadim El Sayed - DAI-Labor, TU-Berlin

libSML is licensed with the GPL, other licenses are available.

### Thanks
Steffen Vogel, Thorben Thuermer, Daniel Pauli, He Bowei

#### Thirdparty Acknowledgements
This product includes software developed for the Unity Project, by Mike Karlesky, Mark VanderVoord, and Greg Williams and other contributors
