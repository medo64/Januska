### Januska Parts

|  # | Part                                      | RefDes  | Preferred Part Number       | Alternate Part Number           |
|---:|-------------------------------------------|---------|-----------------------------|---------------------------------|
|  2 | C 22pF NP0 16V (0805)                     | C1-C2   | 399-8036-1-ND               |                                 |
|  7 | C 100nF X7R 16V (0805)                    | C3-C9   | 478-5311-1-ND               |                                 |
|  1 | C 470nF X7R 16V (0805)                    | C10     | 1276-1199-1-ND              |                                 |
|  3 | C 10uF X5R 16V (0805)                     | C11-C13 | 1276-1096-1-ND              |                                 |
|  4 | D Zener 6.8V 1W (DO-214AC)                | D1-D4   | 3757-1SMA5921_R1_00001CT-ND | SMAZ6V8-FDICT-ND                |
|  2 | DS LED (0805)                             | DS1-DS2 | 475-1415-1-ND               |                                 |
|  2 | F 50mA 60V (1206)                         | F1-F2   | 507-1793-1-ND               | 283-3132-1-ND                   |
|  1 | J USB B, horizontal                       | J1      | ED2982-ND                   |                                 |
|  1 | J MC 1,5/ 3-G-3,81 (3w)                   | J2      | ED2809-ND                   | 277-1207-ND                     |
|  1 | L Ferrite 40Ohm (0805)                    | L1      | 445-2201-1-ND               |                                 |
|  4 | R 120 0.125W (0805)                       | R1-R4   | RMCF0805FT120RCT-ND         |                                 |
|  6 | R 150 0.125W (0805)                       | R5-R10  | RMCF0805FT150RCT-ND         |                                 |
|  2 | R 680 0.125W (0805)                       | R11-R12 | RMCF0805FT680RCT-ND         |                                 |
|  9 | R 1K 0.125W (0805)                        | R13-R21 | RMCF0805FT1K00CT-ND         |                                 |
|  1 | U PIC16F1454 (SOIC-14)                    | U1      | PIC16F1454-I/SL             | PIC16F1454-E/SL                 |
|  1 | U ISL8485IBZ (SOIC-8)                     | U2      | ISL8485IBZ-ND               | 296-1275-1-ND                   |
|  3 | U Optocoupler HL11L1 (SMD-6)              | U3-U5   | H11L1SMCT-ND                | H11L1SR2MCT-ND                  |
|  1 | VR DC-DC 5V->5V 1W (SIP-4)                | VR1     | 945-1655-5-ND               |                                 |
|  1 | Y Crystal 12MHz 50ppm 20pF                | Y1      | 887-2011-ND                 | 887-1238-ND                     |
|  1 | H Enclosure 1593DBK                       |         | HM861-ND                    |                                 |
|  4 | H PCB Screw Self-tapping M3 6mm (#4 1/4") |         | 36-9191-3-ND                | SR6004-ND                       |
|  1 | P MC 1,5/ 3-ST-3,81 (3w)                  |         | ED2876-ND                   | 277-1162-ND                     |

Please note pretty much any of these components can be replaced with a carefully
chosen replacement.


#### Board Size

|       |      Dimensions | Area    | Thickness |
|-------|-----------------|---------|-----------|
| PCB   | 105.0 x 26.0 mm | 4.3 in?? |    1.6 mm |
| Panel |  29.5 x 20.3 mm | 1.0 in?? |    1.6 mm |


#### Jumpers

##### JP1: Termination

If soldered, 120?? termination will be placed between A and B lines.

##### JP2,JP3: Biasing

If soldered, a passive 680?? biasing will be applied.

##### JP4: Readback

If soldered to `ON` position, receiver will not be turned off during
transmission and thus each byte sent will be also received. If soldered to
`OFF` position, turning on transmitter will turn off receiver.


#### Crystal

Crystal is optional but highly recommended if going over 115200 kbps.
