# Stroboscope 125Hz

Stroboscope 125Hz for adjusting teletype baudrate with Arduino Nano.

![](img/StroboPCB.jpg)
![](img/StroboFinish.jpg)

# Using this Stroboscope

Mechanical teletypes has stroboscope markings at the motor axis. This markings are designed to interference with 125Hz.

![](img/StroboFS1.jpg)
![](img/StroboFS2.jpg)
![](img/StroboFS3.jpg)

Dim the room light and lit the markings with the Strobo-LED. If the motor speed is perfect adjusted, the marking stand still.

# Electronic

Designed for an Arduino Nano (or any other Arduino with AVR ATmega328).

![](img/Strobo125.png)

Use a ultra bright white LED and connect it between arduino pin D3 and GND with a serial resistor of 47 Ohm. 

The LED shows NOT the full light to human eyes because the PWM pulses the LED with a duty cycle of 10%.

### Accuracy

![](img/StroboMeas.jpg)

Accuracy is adequate.

# Build Examples

### Torch Light

![](img/StroboFunzel1.jpg)

![](img/StroboFunzel2.jpg)

![](img/StroboFunzel3.jpg)

The Arduino Nano is glued on a cheep torch light with three AAA batteries. The battery voltage is between 4.5V and 3V (empty) and fits the spec of the AVR.
An additional NPN-transistor (BC337) is used to switch the 200mA from the 1Watt LED.
