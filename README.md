# Reed sensor

----
### Description
A ***reed sensor***, also called a ***reed switch***, is an electromechanical sensor that responds to the presence of a magnetic field. When a magnet approaches, the internal contacts close and complete the circuit; when the magnet moves away, the contacts open again.

Typical applications include door and window sensors in alarm systems, fridges, lid detection systems, and many other position-sensing tasks.

[More about reed sensors here](https://uk.rs-online.com/web/content/discovery/ideas-and-advice/reed-switches-guide)

----
### Powering
Typical small reed switches are designed for **low voltage and low current**. They should **not be used directly to switch high‑power loads** without additional circuitry (e.g. a transistor, MOSFET, or relay.)

• Maximum voltage: **12 V**

• Maximum switching current: **20 mA**

• Maximum power: **0.25 W**

----
# Tutorials

----
### 2-pin Reed Switch  standalone (without micro-controllers)

[Tutorial: Turn on a 3V LED with a reed sensor](https://github.com/kingston-hackSpace/Reed_sensor/blob/main/2pin_basic_tutorial_LED.md)

[Tutorial: Turn on a 12V 5W bulb with a reed sensor](https://github.com/kingston-hackSpace/Reed_sensor/blob/main/2pin_basic_tutorial_LED5W.md)

----
### 2-pin Reed Switch (bare) with Arduino

Using the bare 2-pin reed switch requires a pull-up resistor or:

```
pinMode(reedPin, INPUT_PULLUP);
```

[TUTORIAL: 2-pin Reed Switch](https://lastminuteengineers.com/reed-switch-arduino-tutorial/)

[Youtube Video (use for guidance)](https://www.youtube.com/watch?v=iBjNpcQ4fG8&t=23s)


----
### 3-pin Reed Switch Module

This module uses: VCC, GND, Signal. The module already includes a pull-up resistor.

Good for beginners or quick prototyping.

[TUTORIAL: 3-pin Reed Switch with Arduino](https://github.com/kingston-hackSpace/Reed_sensor/blob/main/Reed-module_3pins.md)

----
### 4-pin Reed Switch Module

This module uses: VCC, GND, Digital output, Analogue output (via comparator circuit).

It includes a potentiometer for adjustable sensitivity.

Ideal when you need a cleaner digital signal, you want adjustable trigger behaviour, you are working in a noisy electrical environment

[TUTORIAL: 4-Pin Reed Switch with Arduino](https://arduinomodules.info/ky-025-reed-switch-module/)

