# Riser
![Screenshot](RiserPanel.png)<br>
<br>
# [BOM:Bill of materials](https://github.com/OpenSourceModular/Riser/blob/main/BOM_Riser%20Complete%20Schem_2023-06-17.csv)
## Clocked Stepped Envelope<br>
This an Arduino Nano based eurorack module that uses the MCP4725 DAC Module.<br>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/Ym6SZRJROR8/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
### Inputs:<br>
Clock - input a 5v clock signal - protected from over 5V and under 0V<br>
Reset - input a 5v signal to reset the wave from. The software can also be changed to turn the module into a one-shot envelope generator with each envelope being triggered by this input jack.<br>
Reset Button - used to manually reset the envelope<br>
Amplitude Knob - 0-1V, 0-2V, .... 0-10V<br>
Length Knob - Determines the length of the envelope depending on the ABC switch.<br>
<table>
  <tr>
    <td>
  A:  4, 8,16, 32, 64,128, 256, 512
    </td>
  </tr>
    <tr>
      <td>
  B:  3, 6,12, 24, 48, 96, 184, 368
      </td>
    </tr>
  <tr>
    <td>
  C: 16,32,64,128,256,512,1024,2048
    </td>
  </tr>
</table>
Shape Knob<br>
<table>
  <tr>
    <td>
Ramp Up
    </td>
  </tr>
  <tr>
   <td> 
Ramp Down
     </td>
  </tr>
  <tr>
   <td> 
Ramp Up/Down
     </td>
  </tr>
  <tr>
   <td> 
Sine
     </td>
  </tr>
  <tr>
   <td> 
Exponential Up
     </td>
  </tr>
  <tr>
   <td> 
Exponential Down
     </td>
  </tr>
  <tr>
   <td> 
Log Up
     </td>
  </tr>
  <tr>
   <td> 
Log Down
     </td>
  </tr>
  <tr>
   <td> 
Random
</td>
  </tr>
</table>

CV In - connect 0-5V here. The destination depends on the position of the CV Dest switch. The CV in is added to the knob. It does not subtract.<br> 
<br>
### Outputs:<br>
CV Out - this ouputs 0-10V depending on the amplitude knob.
Pulse - this sends a pulse at the start of each envelope cycle. When in Turing mode, this will output pulses.




