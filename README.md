# KapiBara Electronics Design

That repository holds all the electronics for KapiBara robot. Everything was designed using KiCAD software.

## Boards

- KANGOO - a HAT that connects to Raspberry Pi 5. It delivers +5V using on board buck converter and gives Pi ability to communicate with CAN interface, it also has built in audio codec for microphones ( not used )
- KANGOO_1 - an evolution of KANGOO design it is HAT that connects to Modus extension board, like any other module
- MODUS - an extension board that connect every modules together using standard IDC connectors
- Modus_Extension_Template - a basic template creating standard module compatible with the MODUS board
- MEGANE - a module that handles DC motors control, odometry and orientation estimation using built in IMU and external Magnetrometer
- POWER - a board using for chargin robot's accumulator, it is also responsible for power delivering to entire system
- TWINGO - a module that handles reading state of external touch sensors
- TWINGO_v1.1 - a module that handles reading state of external touch plates, touch is detected by on board RC oscillatros ( not used )