# BirdBox

I would like to make an ESP32 backed project that reads a card scan from an RDM630 and moves a servo based on some logic.

  The device will run on a battery pack and needs to run as long as possible.  The device will need a real time clock, to allow the device to turn off at night to save power.
  Power to the RDM and servo should be gated to prevent power draw when not needed.

  The RDM and servo should draw independent power from the battery, which should come in on microUSB.
  The ESP32 should also have a USB jack and buttons so it can be flashed.
