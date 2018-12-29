# VHF-LNA
VHF Low Noise Amplifier Circuit &amp; PCB using common MMIC. This unit is capable upto 1kW at 2m-band and powered by +12V supply thru separate cable (hi-pwer bias tee is not implemented). MMIC input is protected by A BPF, therefore the input NF is only 1dB (approx.). All the Eagle and Gerber files are included.

## Schematic
![alt text](https://github.com/handiko/VHF-LNA/blob/master/Pics/LNA_sch.png)

## PCB (photos)
* Unpopulated
![alt text](https://github.com/handiko/VHF-LNA/blob/master/Pics/PCB_unpopulated.png)
* Populated. The input port is at near the lower right relay and the output port is at near the lower left relay.
![alt text](https://github.com/handiko/VHF-LNA/blob/master/Pics/PCB_populated.png)

## BPF Response
BPF simulation file (using RFSim99) is included also.
Predicted performance:
* **S21 -3dB from 135.67MHz - 150.07MHz**
* **S21 -10dB from 131.1MHz - 154.5MHz**
* **S21 -0.02dB and S11 -23.86dB at 139.1MHz** (WXSat band)
* **S21 -0.31dB and S11 -11.59dB at 143.02MHz** (BPF Center Frequency)
* **S21 -0.21dB and S11 -13.17dB at 144.3MHz** (EME Band)
* **S21 -0.04dB and S11 -20.69dB at 145.8MHz** (2m AMSAT Band)
* **FM Broadcast band rejection is better than -28dB (S21) at 108MHz**

![alt text](https://github.com/handiko/VHF-LNA/blob/master/Pics/Input_BPF.bmp)
...
