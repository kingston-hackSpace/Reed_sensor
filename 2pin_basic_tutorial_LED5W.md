# Tutorial: Turn-on a 5-12V 10W LED light with a reed sensor

A 10W LED bulb demands more current than what a reed sensor can handle. If the reed sensor is connected to the bulb and power without a MOSFET, the current in the circuit will burn the reed switch. 

For this reason, this tutorial uses an IRLZ44N logic-level MOSFET.

The reed sensor is used only as a **low‑current control signal**.
The MOSFET safely switches the high current required by the LED.

---
### Hardware

- 2-pin reed sensor
  
- 5-12V, 10W(max) LED light (NOT COB lights!)

- MOSFET IRLZ44N (will manage high current and act like a switch)
  
- 100 ohms resistor

- 10K resistor

- Power supply: 5V 2A | 12V 1.5A

- Magnet
  
---
### Note on COB lights

This tutorial is NOT SUITABLE for bare COB lightings such as [COB filaments](https://www.adafruit.com/product/5504) or [COB chips](https://www.voltaat.com/products/2w-cob-led-chip-12v). Among COB lights, only [COB LED strips](https://thepihut.com/products/ultra-flexible-5v-natural-white-led-strip-320-leds-per-meter-1-meter-long-4000k-color) can be used in this tutorial (with the corresponding maximum powering values). COB LED strips have internal circuitry for current limiting, which makes them suitable for this tutorial. 

If using a COB filament is required for your project, you need a *constant-current LED driver* instead of the common power supplied provided by hackSpace.

See more about [LED drivers here] - link pending

---
### Wiring (option 1): Turn LED *ON* when magnet is close

[See diagram here - ON LED]

---
### Wiring (option 2): Turn LED *OFF* when magnet is close

[See diagram here - OFF LED]
