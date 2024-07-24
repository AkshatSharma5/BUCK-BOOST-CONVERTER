# BUCK-BOOST-CONVERTER

## PE Converter - Problem statement:
Solder the components given to realize the non-isolated DC-DC converters with the specifications provided 
as per the specifications provided below. (You are to use the TL 494 IC from for generating the pulses for the 
MOSFET. Solder the components on the TL494 board and test out the pulses (frequency and duty cycle 
variation) before providing the same to the converter. Take suitable precautions such that the drive
circuit ground and the power circuit ground are isolated.

**Buck Converter:**

 - Specifications: Input 25 V, Output 17.5 V, Switching frequency 20
   kHz, Output current 1 A. Waveforms of inductor current and switch
   voltage in CCM.
 - Reduce switching frequency to demonstrate DCM.

   
## HARDWARE IMPLEMENTATION
**1. Breadboard implementation :**

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcwwwlWiEMdthx80MnJlqYOv8t94PKeDkdNUayGRFUOTgnybrTV8dQ4BXKwpI1RMYhmRAIzXjL6a2awvBko9qgbSVBJzEkjIlvmegC3yVuUbp3VnzlyaJ5TT4b4NoZ409J6cuS0yjTXUc9pzAN5ghqRIy1r?key=CoPbelpote_aPOW-jySALA)

  
**2.PWM (used TL 494 IC Soldered Board) :**

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdQL9dZtw5qC2LsZDaB-cosTIyfmmCmKNSJOs1FQPxW6T_1UYwmJ-RafM6wp3aNQFTgl0rNykCVKOYrqOGVrk8XRSh5LNM7UZ8wa3BtQsP8s82_JFjGeazGyz7vxDmUOWhF7UY30-J3DFJhpnAXrvV6nRot?key=CoPbelpote_aPOW-jySALA)
  
**2. Final Design :**

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdw3_IHPG48Db1ewjxU_q8KXgN5aWtHe-CCOoNFQrhrQRM-x2-AnTtcDgG5WFP3heomI4TzZMwjQAUB6yrBrqEkGCsVV3iTjGOJ8hR-R_kAG9wAASFkGz9eZuaLh_SWZi6qsVXXHyqbfwxs8ca1bSt5JGqN?key=CoPbelpote_aPOW-jySALA)


