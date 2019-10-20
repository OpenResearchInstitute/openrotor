# Hardware Design Goals

## Mechanical

* Az/El antenna rotator hardware
* Capable of pointing a 2 meter dish with associated receiver electronics
* All open source
* When possible, standard, easyily sourced components should be used
* Movement speed capable of tracking LEO satellites
* Appropriate enclosure for protection from weather and spray
* Quiet enough to not disturb neighbors

## Electrical Control System

* Should interface with on/off, DC Drive, or Stepper motors (perhaps with optional hardware addons)
* Should accept position feedback from analog sensors, homing switches, or encoders
* Capable of running open-loop or closed loop (preferred)
* Optional capability for position sensing through IMU
* Optional GPS for location and time sync
* Supports control by hamlib, common serial rotor protocols, N1MM rotor protocol, and additional networked methods


