REGULATED POWER SUPPLY

A portable regulated power supply design using KiCad. It can switch between 3.3V and 5V as we need to. It is used in projects with development boards.

TABLE OF CONTENTS

Components

connections

Schematic

3-D view

gerber view

Components

9V-Battery--1

LM7805 Voltage regulator IC--1

LM1117-3.3V IC--1

capacitor-16V 10Microfarad--2

Capacitor-10V 10microfarad--2

SPDT switch

Connecting wires

Load


CONNECTIONS

Connections are made as follows:

Connect each 16V 10microfarad capacitor between Vin and gnd terminals of LM7805 and LM1117 Voltage regulator ICs

Connect each 10V 10microfarad capacitor between Vout and gnd terminals of LM7805 and LM1117 Voltage regulator ICs

9V(+ve) --> Vin of LM7805 and LM1117

9V(-ve) --> gnd of LM7805 and LM1117

Vout of LM7805 --> NC terminal of SPDT

Vout of LM1117 --> NO terminal of SPDT

+ve of load --> common of SPDT

-ve of load --> common gnd

SCHEMATIC

The following Schematic was made by using KiCad

![Screenshot 2025-04-14 132233](https://github.com/user-attachments/assets/c4502b89-29c2-40a8-b179-36b4a196b803)


3-D view

This is how the final output looks like

![Screenshot 2025-04-14 132525](https://github.com/user-attachments/assets/162dfa33-bbbc-4200-b01f-53db5e6631ba)


gerber view

[regulated power supply-job.zip](https://github.com/user-attachments/files/19757120/regulated.power.supply-job.zip)
