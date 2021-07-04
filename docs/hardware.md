# Hardware Design Goals

## Mechanical

* Az/El antenna rotator hardware
* Capable of pointing a 2.1 meter dish with associated electronics
  * Maximum weight of dish and electronics (Vertical Load): nnn kg
* All open source
* When possible, standard, easily sourced components should be used
* Movement speed capable of tracking LEO satellites
* Appropriate enclosure for protection from weather and spray
* Quiet enough to not disturb neighbors
* 3 inch mast
* Rotational Torque
  * Elevation: nnn N&sdot;m
  * Azimuth: nnn N&sdot;m
* Braking Torque
  * Elevation: nnn N&sdot;m
  * Azimuth: nnn N&sdot;m
* Pointing Accuracy
  * Elevation:  &pm;nnn&deg;
  * Azimuth: &pm;nnn&deg;
* Range of Travel
  * Elevation: +nnn&deg; to -nnn&deg;
  * Azimuth: +nnn&deg; to -nnn&deg;
* Speed of Travel
  * Elevation: nnn&deg;/s
  * Azimuth: nnn&deg;/s

## Electrical Control System

* Should interface with on/off, DC Drive, or Stepper motors (perhaps with optional hardware add-ons)
* Should accept position feedback from analog sensors, homing switches, or encoders
* Capable of running open-loop or closed loop (preferred)
* Optional capability for position sensing through IMU
* Optional GPS for location and time sync
* Supports control by hamlib, common serial rotor protocols, N1MM rotor protocol, and additional networked methods such as MQTT.


