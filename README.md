<img src="https://capsule-render.vercel.app/api?type=waving&color=0:022c22,100:166534&height=140&section=header&text=Embedded%20%C2%B7%20PCB%20%C2%B7%20Machines&fontSize=38&fontColor=ffffff&desc=Burhanudin%20Yusuf%20Habibi&descAlignY=72&descAlign=50&fontAlignY=38" width="100%"/>

### I build the electronics and the firmware that run industrial machines.

ESP32 controllers, operator panels, sensor and power wiring, and the PCBs those circuits live on. The work below is on real roasters, not classroom boards.

<p>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32"/>
<img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white" alt="KiCad"/>
<img src="https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&logo=platformio&logoColor=white" alt="PlatformIO"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
<img src="https://img.shields.io/badge/PCB_layout-14532d?style=for-the-badge" alt="PCB"/>
</p>

## What I do

| | |
|---|---|
| **Firmware** | ESP32, C++, PlatformIO. Closed-loop control, Modbus RTU, field debugging on a live machine |
| **Electronics** | Schematic and PCB in KiCad. Logic board separated from the mains and power board |
| **Machines** | Thermocouples, Nextion HMI, gas valves, heaters, VFDs, contactors, safety interlocks |
| **Bring-up** | Trace a bad reading to the sensor, the UART, or the board — then change one thing and measure again |

## Selected work

| Project | What I owned | What it does |
|---|---|---|
| **[Orion 05](https://github.com/byhabibi/orion-05)** | Firmware on the machine | Gas drum roaster. Bean, environment, and motor thermocouples. Gas-valve servo, exhaust dimmer, pressure and gas sensing, roast curve, safety shutdown |
| **[D01E](https://github.com/byhabibi/d01e-roaster)** | Firmware and the PCBs | Electric drum roaster, 3.6 kW heater. ESP32 controller plus two boards: main control and power I/O |
| **[D03](https://github.com/byhabibi/d03-pcb)** | PCB design | Two boards for a 3 kg gas roaster. DevKit seat, fixed 5 V supply, three thermocouple modules, contactors on the power board |

## Why this is useful on a line

A controller that only works on the bench is not finished. These projects had to survive panel noise, a heater or a gas valve that must not jump, and an operator screen that stays readable. Power and logic are split onto separate boards so a mains fault does not sit on the microcontroller.

## Also

Linux, Docker, and CI/CD, from earlier infrastructure work. [Production stack](https://github.com/byhabibi/production-stack-dev) · [Lab](https://lab.bybi.web.id) · [Notes](https://github.com/byhabibi/devops-stack-learn)

[bybi.web.id](https://bybi.web.id) · [github.com/byhabibi](https://github.com/byhabibi)
