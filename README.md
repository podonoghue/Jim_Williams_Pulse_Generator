# Jim_Williams_Pulse_Generator
    
**Note:  The operation of this circuit depends on the breakdown characteristics of the 2N2369 transistor used.**

**Please refer to the Application notes provided.**  

I had no problems with the boards I constructed but I have had reports of the circuit not working.  The 2N2369 transistors appears to be no longer available. I have no experience with using the circuit with 2N2369A or BSX20 devices.

This module produces a pulse with a very fast rise time.   
Its main use is for testing oscilloscope rise-time and hence estimating bandwidth.  
For convenience the module is powered from a micro-usb socket.  
Most current oscilloscopes have a USB host socket that can provide the power needed.   
Connection to the oscilloscope will require a BNC-to-BNC adapter.  
A length of 50ohm coax should be used to extend the pulse so that rise-time may be measured.  

References:  
<a href="http://cds.linear.com/docs/en/application-note/an72f.pdf">A Seven-Nanosecond Comparator for Single Supply Operation, Linear Technology’s Application Note 72, May 1998</img></a>  
<a href="http://cds.linear.com/docs/en/application-note/an47fa.pdf">High Speed Amplifier Techniques, Linear Technology’s Application Note 47, August 1991</img></a>  

This is an Altium designer project.  

Refer to the PDFs in the Project Outputs directory for layout and BOM
<a href="https://github.com/podonoghue/Jim_Williams_Pulse_Generator/blob/master/Hardware/Project Outputs for Pulser/Pulser.PDF">PDF Documentation</img></a>

# Top Image  
![Top image](https://raw.githubusercontent.com/podonoghue/Jim_Williams_Pulse_Generator/master/Hardware/Pulse_Top.png "Top Board Image")  
# Bottom image  
![Bottom image](https://raw.githubusercontent.com/podonoghue/Jim_Williams_Pulse_Generator/master/Hardware/Pulse_Bottom.png "Bottom Board Image")  
# 3D Image  
![3D image](https://raw.githubusercontent.com/podonoghue/Jim_Williams_Pulse_Generator/master/Hardware/Pulse_3D_Perspective.png "3D Board Image")  
# Example waveforms from 500MHz DSO, 50R termination direct connection to BNC input
![Measured Waveform](https://raw.githubusercontent.com/podonoghue/Jim_Williams_Pulse_Generator/master/Hardware/Waveform_500MHz_50R_DSO.png "Measured Waveform")
![Measured Waveform](https://raw.githubusercontent.com/podonoghue/Jim_Williams_Pulse_Generator/master/Hardware/Waveform_500MHz_50R_DSO_rising_edge.png "Measured Waveform")
# Example waveforms from 500MHz DSO, 500MHz probe with BNC converter
![Measured Waveform](https://raw.githubusercontent.com/podonoghue/Jim_Williams_Pulse_Generator/master/Hardware/Waveform_500MHz_Probe_500MHz_DSO_rising_edge.png "Measured Waveform")
  
PCBs may be ordered from OSH park<a href="https://oshpark.com/shared_projects/KrhgN8JM"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>  



