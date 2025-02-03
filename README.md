# Big Box Amiga Action Replay III remake

This repository contains the reverse engineering schematic for the Amiga Action Replay III and everything needed to build it.<br>
<br>
<b>ATTENTION! Project not yet verified and tested</b>
<br>
![alt text](https://github.com/na103/bbar3/blob/main/IMG/bbar3.png "BBAR3")
<br>
<br>

## Board bill of materials
| Qt. |    Description     |             Designator          |    Mouser part     |             Note              |
|:---:|--------------------|---------------------------------|--------------------|-------------------------------|
|6    |Resistor 1K         |R1-R4, R6, R7                    |CRCW12061K00FKEA    |                               |
|17   |Resistor 4.7K       |R5, R8-R23                       |CRCW12064K70FKEA    |                               |
|1    |Cap. 10uF 16V       |C1                               |EEA-FC1E100H        |                               |
|4    |Cap. 100nf          |C2-C5                            |C1206C104K5RAC7867  |                               |
|1    |Cap. 1uF 63V        |C6                               |ESS105M050AB2AA     |                               |
|5    |GAL16V8             |U1-U5                            |ATF16V8BQL-15JU     |                               | 
|5    |PLCC 20 POS Socket  |U1-U5                            |540-88-020-17-400-TR| Optional                      |
|1    |74F74               |U6                               |SN74LS74ANSR        |                               |
|2    |27C010 OTP EPROM    |U7, U9                           |AT27C010-70JU-T     |                               |
|1    |SRAM 64K            |U8                               |AS6C6264-55SCN      |                               |
|1    |SRAM 256K           |U10                              |AS6C62256-55SCN     |                               |
|1    |MC1455              |U11                              |MC1455DR2G          |                               |
|2    |ZVP2106A            |Q1, Q2                           |ZVP2106A            |                               |
|1    |Diode               |D3                               |LL4148-M-18         |                               |
|1    |2.54MM 10P VERT HDR |J1                               |70246-1004          |                               |
|1    |SPDT ON-ON switch   |SW1                              |MHSS1104            |                               |

## Remote control bill of materials
| Qt. |    Description     |             Designator          |    Mouser part     |             Note              |
|:---:|--------------------|---------------------------------|--------------------|-------------------------------|
|1    |Trimmer 10K         |VR1                              |RV09AF-40-20K-B10K  |                               |
|1    |Button switch red   |SW1                              |D6C40F1LFS          |                               |
|1    |SPDT ON-ON switch   |SW2                              |2MS1T1B3M2QES       |                               |
|1    |IDC 10pos 6in cable |                                 |HCSD-05-S-06.00-01-N-ST4|                           |
|1    |2.54MM 10P VERT HDR |J1                               |70246-1004          |                               |


<br><br>

If you found this my work useful, please consider buying me a cup of coffee if you want:<br>
<a href='https://ko-fi.com/na103' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/cup-border.png' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

# License

This work is licensed under a Creative Commons Attribution 4.0 International License. See [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

