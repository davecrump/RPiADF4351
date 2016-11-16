# RPiADF4351
Control an ADF4351 using spi on any GPIO pins from a Raspberry Pi

call using sudo ./adf4351 fff.f

fff.f is the frequency in MHz (>35 and <4400)

or sudo ./adf4351 off to turn the VCO off

GPIO pins for LE, CLK and DATA can be set in adf4351.c using wiringPi numbering.
