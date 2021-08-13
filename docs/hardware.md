# Hardware Design Goals

## Mechanical

* Az/El antenna rotator hardware
* Capable of pointing a 2.1 meter dish with associated electronics
  * Maximum weight of dish and electronics (Vertical Load): 50 kg
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
  * Elevation:  &pm;0.1&deg;
  * Azimuth: &pm;0.1&deg;
* Range of Travel
  * Elevation: 0.00&deg; to +180.00&deg;
  * Azimuth: 0.00&deg; to +450.00&deg;
* Speed of Travel
  * Elevation: 3.0 &plusmn; 0.5&deg;/s
  * Azimuth: 6.0 &plusmn; 0.5&deg;/s

## Electrical Control System

* Should interface with on/off, DC Drive, or Stepper motors (perhaps with optional hardware add-ons)
* Should accept position feedback from analog sensors, homing switches, or encoders
* Capable of running open-loop or closed loop (preferred)
* Optional capability for position sensing through IMU
* Optional GPS for location and time sync
* Supports control by hamlib, common serial rotor protocols, N1MM rotor protocol, and additional networked methods such as MQTT.


