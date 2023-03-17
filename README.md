# Boost converter

## Project status 
Manufactured, assembled, not tested yet

## Project overview

Small boost converter PCB that can be used for small projects, the converter is based on MT3608 IC, which is a cheap IC manufactured by different chinese companies.
The input voltage can be from 2V to 24V, the output can be set up to 28V.
According to the datasheet, the output current limited by the switch is 4A, I've not tested the circuit yet but for high currents thermal dissipation must be taken into account. The datasheet doesn't specify thermal resistance so it will be hard to assess the real acceptable current, I'll update about my findings after some inital tests.\
The switching frequancy of the converter is 1.2MHz.\
The IC has undervoltage lockout, current limiting, thermal and overload protection 

The dimension of the PCB are 33mm X 15mm, it is a 2 layers PCB with compoenents assembled only on the TOP layer

Top view - \
![image](https://raw.githubusercontent.com/SeryDesigns/Boost-converter/main/docs/TOP.png)
\
Bottom view -  \
![image](https://raw.githubusercontent.com/SeryDesigns/Boost-converter/main/docs/BOTTOM.png)

I've created a short time lapse video of the design process, you can click the link below to check it out on my YouTube channel \
[![Boost converter PCB design in 5 minutes (time lapse)](https://img.youtube.com/vi/zZR8q_p8QZo/hqdefault.jpg)](https://youtu.be/zZR8q_p8QZo)

