[<Back](https://team-208-github-io.github.io/egr314-team208.github.io/)

# EGR 314 Team 208 Verification Table 
* Kyle Selasky, Felicia Szleszinski, Miles Wilson, Mingqi Yu											

| |EIKS AC-DC 5V 1A Wall Charger Power|Switching Voltage Regulator LM2575|Microcontroller PIC16F18876-I/PT|Force Sensor GHF-10|Force Sensor Op-Amp|ADC SPI for Force Sensor|Temp Sensor TC74A4|JSX5300-370 Motor|Motor Driver IFX9201SGAUMA1|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|
|EIKS AC-DC 5V 1A Wall Charger Power|v (VG, 04/19/2023)|v (VG, 04/19/2023)|nc|nc|nc|nc|nc|nc|nc|
|Switching Voltage Regulator LM2575| |v (VG, 04/19/2023)|v (VG, 04/19/2023)|nc|nc|nc|nc|nc|nc|
|Microcontroller PIC16LF1576-I/PT| | |v (VG, 04/19/2023)|nc|nc|v (VG, 04/20/2023)|v(VG, 04/19/2023)|nc|v (VG, 04/19/2023)|
|Force Sensor GHF-10| | | |v (VG, 04/20/2023)|v (VG, 04/20/2023)|nc|nc|nc|nc|
|Force Sensor Op-Amp| | | | |v (VG, 04/20/2023)|v (VG, 04/20/2023)|nc|nc|nc|
|ADC SPI for Force Sensor| | | | | |u|nc|nc|nc|
|Temp Sensor TC74A4| | | | | | |v (VG, 04/19/2023)|nc|nc|
|JSX5300-370 Motor| | | | | | | |v (VG, 04/19/2023)|v (VG, 04/19/2023)|
|Motor Driver IFX9201SGAUMA1| | | | | | | | |v (VG, 04/19/2023)|
|Key| | | | | | | | | |
|u|unverified connection/subsystem| | | | | | | | |
|x|connection verified by you| | | | | | | | |
|v (XYZ, 1/23/45)|connection verified by instructors (INITIALS, date)| | | | | | | | |
|(xyz)|serial protocol| | | | | | | | |

# Decision making process
  Our decision making process was to include components that would allow us to meet the project requirements. For our glove we include an LM2575 surrace mount voltage regulator that takes 5V and outputs at 3.3 V. Our PIC16LF1576-I/PT has 44 pins and is able to communicate in both SPI and USART, meeting the requirments for the communication protocl. Our temperature snesor and force sensor helps us meet he requirmenets to have two different environmental sensors


# System Working at the ASU Innovation Showcase:

![verification pic](https://user-images.githubusercontent.com/122938115/235548959-5a52d474-cf31-4234-8153-94767c5ff151.jpg)

[Link to Innovation Showcase Demo on Google Drive](https://drive.google.com/drive/u/1/folders/150sbrrwfcBK8OzjsMLOthqIVqgtNKn3C)
