# Wind Sensor Lab

### CE 415 - Environmental Measurements

Source code and reference material for the wind sensor lab.

* [Wiring Diagram](wiring.md)

## The Lab

The purpose of this lab is familiarize students with common wind sensors 
(cup & vane anemometer and ultrasonic anemometer) and with programmable
data loggers. You will be:

* connecting the sensors to the datalogger
* monitoring real-time data

### Part I

In the first part, the sensors are connected to the data logger with cables.
Each cable has labels indicating the sensor model and meaning of each wire.
Refer to the [wiring diagram](wiring.md) for this part. You may also find the
Quick Start section of the user manuals to be useful (see *References* below).

1. Ensure the data logger is turned off before connecting wires. The power
   switch is located near the red LED on the power supply ("PS100").
2. For each cable, plug the appropriate end (with connector) into the sensor.
   Refer to the user manual for correct insertion technique to avoid damaging
   the sensor.
3. For each wire of each cable:
    1. Identify the corresponding data logger terminal from the wiring diagram
    2. Open the terminal completely with a flat-blade screwdriver by turning 
       counter-clockwise.
    3. Hold the bare wire end in the terminal
    4. Close the terminal (turn clockwise) to clamp the wire; secure tightly 
       enough so wire cannot be tugged out but not so tight as to stress or
       deform the terminals.

### Part II

Real-time data can be monitored from the remote keypad ("CR1000KD"). Things you
might try:

* blow across the sonic anemometer transducers are various angles and examine
  effects on 3D components `Ux`, `Uy`, and `Uz`
* stick your hand between the transducers and observe data (is there a way to
  detect this "problem"?)


## References

* Campbell Scientific, Inc. *CR1000 Measurement and Control System Operator's
  Manual.* Revision 2015 Apr 13. Online:
  <https://s.campbellsci.com/documents/us/manuals/cr1000.pdf>

* Campbell Scientific, Inc. *CSAT3B Three-Dimensional Sonic Anemometer
  Instruction Manual.* Revision 2016 May. Online: 
  <https://s.campbellsci.com/documents/us/manuals/csat3b.pdf>
  
* Campbell Scientific, Inc. *Met One 034B Wind Set Instruction Manual.*
  Revision 2016 Sep. Online:
  <https://s.campbellsci.com/documents/us/manuals/034b.pdf>
