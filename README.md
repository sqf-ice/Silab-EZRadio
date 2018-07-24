# Silab-EZRadio
Si1064 based RF 2GFSK communication example

# Transmitter with Sleep Functionality 
- Water sensor interrupt 
- Suspend Sleep mode idle
- When sensor interrupt, transmitt RF packet

# RF Receiver for Controller
- Si1064 based 2GFSK receiver
- Send GPIO Signal for 1 sec when packet has received

# Particle Photon based controller
- DFPlayer via Serial1
- GPS via Software Serial
- Interrupt checking
- NeoPixel Drawing Pattern when rf packet is received
