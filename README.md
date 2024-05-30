# Cascade Control Proposal for the Attitude of a CubeSat 1U Satellite.
Research project where was developed a new Guidance, Navigation and Control (GNC) law for Attitude Determination and Control Systems (ADCS) of CubeSat satellites. 

## Year: 2016. 

## Simulations. 

### Reaction Wheel Model in Simulink. 

An early version of the RW model. 
Used the motor properties obtained from a previous project in which a DCPM motor was characterized. 

![RW1](https://github.com/Lechuga-Geronimo/AttitudeControlCubeSatSatellite/assets/142461885/962b0b65-9436-4cdc-8b09-4b21348480f5)

### Cascade Control in Simulink. 

A multi-loop (two control loops) for the attitude control of a 1U CubeSat. 
The inner loop is about the dynamics of the characterized RW.
The external loop is about the satellite dynamics. 

![rw2](https://github.com/Lechuga-Geronimo/AttitudeControlCubeSatSatellite/assets/142461885/ff853487-f843-4bca-a300-09c93a814c73)

### Attitude Control in Simulink. 

Cascade control response with enviromental disturbes included. 

In figure:

* Magenta: reaction wheel's angular speed (\omega_r(t)).
* Red: satellite attitude in (roll (x(t))).
* Cyan: setpoint, from 0 to 1° in 10 seconds.

![RW3](https://github.com/Lechuga-Geronimo/AttitudeControlCubeSatSatellite/assets/142461885/8753b4e6-e372-4b87-87bc-1ec446a95f9a)

