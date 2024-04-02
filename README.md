# LEMOS-6

## General Information
- _decayingTurbulenceInflowGenerator_ boundary condition for LES in OpenFOAM, originally developed by Chair of Modeling and Simulation (LEMOS), University of Rostock. The original repository is https://github.com/LEMOS-Rostock/LEMOS-2.4.x 
- LEMOS-6 is adapted version compatible with OpenFOAM-6 by Danh Nam Nguyen 

## Installation
- Prepare a directory on your system, e.g., _yourDirectory_:

		mkdir ~/OpenFOAM/yourDirectory/
		cd ~/OpenFOAM/yourDirectory/	
- Download source files using git: 

		git clone https://github.com/danhnam11/LEMOS-6.git

- To compile this library, go to _LEMOS-6/inflowGenerator_ directory and type _wmake_:

		cd ~/OpenFOAM/yourDirectory/LEMOS-6/inflowGenerator/
		wmake

- After compiling, the library is stored at _$FOAM_USER_LIBBIN_ directory. Now it is ready to be used.

## Using this library for LES in OpenFOAM
A tutorial for LES of a cryogenic nitrogen jet is available in here (in _tutorials_ directory): https://github.com/danhnam11/realFluidFoam-6 
