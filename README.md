# 12-bit-500MSPS-current-steering-DAC

This project focuses on a 12-bit segmented DAC with thermometer-coded 6-bit MSBs and binary-coded 6-bit LSBs.

### Design Parameters and Specifications:
| **Parameter**           | **Specification** |
| ----------------------- | ----------------- |
| Supply Voltage (VDD)    | 1.2 V             |
| Technology              | 65 nm CMOS        |
| Resolution              | 12 bits           |
| Sampling Frequency (Fs) | 500 MS/s          |
| SFDR                    | 70 dB @ 250 MHz   |
| ENOB                    | 11 bits           |
| Power Consumption       | 60 mW             |

### PVT Conditions:
| **Condition**  | **Range**        |
| -------------- | ---------------- |
| Process        | 65 nm CMOS       |
| Supply Voltage | 1.08 – 1.32 V    |
| Temperature    | −40 °C to 125 °C |

*****************
### Implementation:
<img width="1134" height="562" alt="image" src="https://github.com/user-attachments/assets/eafd1b20-15b3-444c-b135-66d014c088ec" />

### Testbench Schematics:
<img width="1593" height="573" alt="image" src="https://github.com/user-attachments/assets/d130644c-1e5c-40e0-863f-b3511db9c6e1" />

### Layout DAC:
<img width="909" height="512" alt="image" src="https://github.com/user-attachments/assets/4139dba4-ca19-4325-9cd0-95be87972428" />

### Static performance:
### INL
<img width="1038" height="835" alt="image" src="https://github.com/user-attachments/assets/f296df3d-de98-46f3-b3c7-1b4fd25db127" />

### DNL
<img width="1022" height="822" alt="image" src="https://github.com/user-attachments/assets/32ae3a52-a723-4091-9c31-616e9a172e32" />

### Dynamic performance:
<img width="1848" height="854" alt="image" src="https://github.com/user-attachments/assets/b0374b8a-98d4-4b14-8ee9-ec8c2eacd9f2" />

### Spectrum:
<img width="1581" height="746" alt="image" src="https://github.com/user-attachments/assets/49f17a2e-f684-4e61-ba6d-daeb926d48e3" />

*****************
### Key References:

[2] G. Manganaro, Advance Data Converters. Cambridge University Press, 2012.

[4] P. Caragiulo, C. Daigle, and B. Murmann, DAC Performance Survey 1996-2020,” [Online]. Available: https://github.com/pietro-caragiulo/survey-DAC.

[6] C. -H. Lin et al., "A 12 bit 2.9 GS/s DAC With IM3 ≪− 60 dBc Beyond 1 GHz in 65 nm CMOS," in IEEE Journal of Solid-State Circuits, vol. 44, no. 12, pp. 3285-3293, Dec. 2009.

[11] G. M. Hong, Shih-Hsuan Hsu, Yan-Hua Peng, Alvin Hsin-Hung Chen, Yi-Ti Wang and Hsin-Hung Lu, "A 10-bit 300MHz 0.1mm2 triple-channel current-steering DAC 75.98dB SFDR in 65nm," 2008 IEEE International Symposium on VLSI Design, Automation and Test (VLSI-DAT), Hsinchu, 2008.

[19] Wei-Hsin Tseng, Chi-Wei Fan, and Jieh-Tsorng Wu. A 12-bit 1.25-gs/s dac in 90 nm cmos with 70 db sfdr up to 500 mhz. Solid-State Circuits, IEEE Journal of, 46(12):2845–2856, 2011.

[20] A. Van den Bosch et al., "A 12 bit 200 MHz low glitch CMOS D/A converter," Proceedings of the IEEE 1998 Custom Integrated Circuits Conference (Cat. No.98CH36143), Santa Clara, CA, USA, 1998.

[21] J. Deveugele and M. Steyaert, "A 10b 250MS/s binary-weighted current-steering DAC," 2004 IEEE International Solid-State Circuits Conference (IEEE Cat. No.04CH37519), San Francisco, CA, USA, 2004.

[22] R. L. Nguyen et al., "8.6 A Highly Reconfigurable 40-97GS/s DAC and ADC with 40GHz AFE Bandwidth and Sub-35fJ/conv-step for 400Gb/s Coherent Optical Applications in 7nm FinFET," 2021 IEEE International Solid-State Circuits Conference (ISSCC), San Francisco, CA, USA, 2021.

*****************


*****************

