Mario Estrada Period 6
Getting the pins right is very important. I accidentally conncted the LED to the 3.3V pin rather than the GPIO 17 pin
3.3 V is safe because Raspberry Pi GPIO uses 3.3 V logic.
A resistor protects the LED and Pi.
Wrong BCM pin = the code controls the wrong pin.
GPIO.cleanup() resets the pins after the program ends.

Safety/troubleshooting: I double-checked wiring, voltage, and pin numbers.


