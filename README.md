# Electronics-Thermometer
Proteus Simulation File For MicroElectronics Circuits course project (ELC)
## Project topic: Electronics Thermometer  
## Name: Abhijith Rajeev Menon
## Roll Number: AM.EN.U4ELC19002

## Electronics Thermometer
(a.k.a. Temperature Indicator)

### Introduction 

Electronics thermometer is a substitute for the normal mercury thermometer, which is easy to handle as well as durable. The thermometer / indicator that I designed, is simulated on Proteus 8 simulator and works on the same principle of temperature sensing, amplifying and indicating.

### Components Used

1)Operational amplifier - lm324 
2)Temperature sensor - lm35 
3)Resistors of different specifications
4)LED - green for indication 
5)Voltage source 


### Design

1) The main part of a electronics thermometer is the temperature sensor. So 	selecting a temperature sensor is the most important part of the design. In Proteus, 	lm35 is a precision centigrade temperature sensor which can detect temperature in 	a range of (-55 to 150 degC). 

2) Now check the corresponding voltages obtained at different temperatures. In 		lm35 voltages for corresponding temperature is as follows 
For 32 degC the voltage will be 3.2x , for 46 degC the voltage will be 4.6x. So for 	obtaining temperature , we should amplify the sensor output by 10. So gain 	A=10.

3) Now for the operation amplifier design :
 A = 10 and non inverting topology, let Rf = 9k and Ri = 1k 

The temperature sensing is completed. Now for a display interface, we can either pair it up with an Arduino component, or to make it more simpler I have designed it as a simple led green indication circuit. The circuit is as shown in the simulation Diagram. It uses simple resistor logic and follows a reference voltage for led indication. 






### Simulation Diagram








### Results and Conclusion
