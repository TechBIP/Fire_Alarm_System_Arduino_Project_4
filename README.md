# Fire_Alarm_System
This Project Repository is all about an creating a Fire alarm system.

# Circuit componenets required:-
Arduino uno board, led, 3 resistors, piezo, gas sensors, temperature sensors.

# Software Required:-
NOTE******** this project can be prepared both using software and hardware.

For hardware:- Make sure that you have all the required circuit components, and AARDUINO IDE installed.

For Software:- open an tinkercad account you can design and simulate your design online.

# Circuit Connection:-
1. Connect the lower three terminals, that is terminal B1, H2, B2 to the positive terminal which is connected to the power of arduino i.e. 5v.
2. connect the A1 of gas sensor to A0.
3. connect the gnd of the gas sensor to gnd of arduino.
4. connect a resistor to the terminal A2 of the gas sensor and then gnd it.
5. connect the power of the temperature sensor to the power of the arduino.
6. connect the vout to pin A1 .
7. connect the gndto gnd of arduino.
8. connect the cathode to the gnd.
9. connect the resistor to anodeof led and then connect it to D13.

# Result:-
On simulating the circuit, we can see the output on the serial monitor. So, initially there is a value of gas sensor of about 85 and the value of temperature 24.78 , now when the gas is concentrated more in front of the gas sensor we can see that , the value of gas sensor increases. now, on increasing the temperature, the red led, glows for alerting purpose which is specifying that the firealarm piezo to ring continuosly as well as for alert part. Thus, we can create a fire alarm system using Arduino uno.

# contribution:-
contributions are welcome. if you have anything to add to this project feel free to contribute to this repository.
