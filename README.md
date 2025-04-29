Circuit Diagram & Connections:
Assemble the circuit as shown in the figure below


1.	For PIR sensor, connect ground pin to gnd of arduino, out pin to 2nd pin of arduino and vcc to vcc(5v) of arduino.
2.	For buzzer, connect one end to gnd of arduino and other end to 6th pin of arduino.

3.	For resistor, connect one end to gnd and other end to A0 pin of arduino.

4.	For LDR, connect one end to 5v and other end to A0 pin of arduino.

5.	For LED, connect one end to gnd and other end to 5th pin of arduino.

6.	For battery, connect one end to gnd and other to vin of arduino.

With the help of USB cable connect arduino to the system and through arduino software dump the code into it and execute it, to get the output.
 
Working of PIR Sensor:
PIR sensors are more complicated than many of the other sensors because there are multiple variables that affect the sensors input and output. The PIR sensor itself has two slots in it, each slot is made of a special material that is sensitive to IR. The lens used here is not really doing much and so we see that the two slots can ‘see’ out past some distance (basically the sensitivity of the sensor). When the sensor is idle, both slots detect the same amount of IR, the ambient amount radiated from the room or walls or outdoors. When a warm body like a human or animal passes by, it first intercepts one half of the PIR sensor, which causes a positive differential change between the two halves. When the warm body leaves the sensing area, the reverse happens, whereby the sensor generates a negative differential change. These change pulses are what is detected.
Working of the Project:
The circuit is infact a dark activated switch that measures the ambient light level and will enable the system only when ambient light level is below a threshold value. Here an LDR (Light Dependent Resistor) is used to measure the light level. The alarm system is triggered when a “Logic High (H)” level signal is detected at its sensor input port. The best sensor you can use to detect an intrusion is the Passive Infrared (PIR) Sensor. The PIR Sensor detects the motion of a human body by the change in surrounding ambient temperature when a human body passes across, and effectively controls the switching when it detects a moving target.

 
