# Reed sensor

Also called a *reed switch*, it responds to changes in a nearby magnetic field. When a magnet approaches, the internal contacts close and complete the circuit; when the magnet moves away, the contacts open again.

Typical applications include door and window sensors in alarm systems, fridges, lid detection systems, and many other position-sensing tasks.

You can find them as a bare two-pin switch, or mounted on a small module with three or four pins.

----
# Tutorials
----
### 2-pin Reed Switch (bare)

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

