# LED_Blinking_IOT

# Internet of Things
# First IOT Simulation
Thinkercad is a web based simulation software through which we can create a 3D modeling (i.e physical design of items), which is free to use and very handy for making circuits or simply as for creating IOT simulations without physical devices.

# Arduino
Arduino is a microcontroller with digital and analog i/o pins, memory and a processor.

# Blinking a LED with Thinkercad
# LED
	Here, the LED has its anode end and cathode end. Cathode is grounded and anode is set as output in pin 4 (can pick any pin from 1-13).
Register
	We add register to the cathode so as to increase the life span of the led because the output current coming from the led 4 will be more than 20 mA (which is the maximum recommended current).
	Take register with resistance 200-250 ohm. As,
	V = I (R+r), 
Considering V voltage to be 5 v,
I to be 20 mA which is recommended maximum current
r to be internal resistance of the LED.
	Thereby we get R to be 230 Ohm. So, we use are using resistor with resistance of 230 Ohm.
  
  ![image](https://user-images.githubusercontent.com/40635491/156864936-44336c88-e5f4-4b0d-8758-65da91630be2.png)
