There was an issue installing this on a OPZ (1, probably Allwinner H2), Armbian with a Trixie-base and Python 3.13.5 where the system complained about a signed and an unsigned integer being compared in pyA20/gpio/port/port.c.
I highlighted the problematic section. This is a bodge job, unless you run into this very specific problem, don't use this project. Instead, refer to d0kin's repo: https://github.com/d0kin/OrangePi0-PyH2-gpiolib

# OrangePi0-PyH2-gpiolib

Orange pi zero python gpio lib based on olimex pyA20 https://pypi.python.org/pypi/pyA20/0.2.12 library

## gpio pinout
      
      
![Preview](https://raw.githubusercontent.com/Sputkin/OrangePi0-PyH2-gpiolib/master/img/pinout.jpg)

Thanks 0SHLAB.com for the photo


## installation
	
	cd OrangePi0-PyH2-gpiolib	
	python setup.py install



