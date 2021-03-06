# ulx3s_demos
Testing area for ULX3S and store for bitstreams.

First upload: simplesoc.bit

## Simple 16 bit RISC SoC. 
Loosely based on the Acorn Atom. The SoC is a 16 bit RISC with 16 registers. Each register is 16 bit wide.\
To demonstrate the SoC a simple BASIC version was written in C++ and also a 3D demo.



### Requirements:

 ULX3S - 85k.\
 USB OTG cable\
 PS/2 supporting USB keyboard\
 HDMI cable and monitor\
 OR: HDMI cable and HDMI2USB adapter (as used in the screenshots below.)\
 
 OTG cable connected to us2.
 
### Starting the demo:
type DEMO on the prompt and press enter.

![3D Demo running on SimpleSoC](screenshots/simplesoc_2.png?raw=true "3D demo")

### Creating a BASIC program:

type AUTO and enter.
The prompt will auto increment the BASIC line number and pressing Escape will end the editor.

### Running a BASIC program:
type RUN and enter.

![BASIC running on SimpleSoC](screenshots/simplesoc_1.png?raw=true "BASIC demo")
