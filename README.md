# EXPERIMENT-NO--04-Distance measurement using Ultrasonic sensor
 ###  DATE: 

###  NAME: NARMADHA SREE S
###  ROLL NO :212223240105
###  DEPARTMENT:AI&ML
## AIM: 
To interface an ultrasonic pair and measure the distance in centimeters , calculate the error
 
### COMPONENTS REQUIRED:
1.	ultrasonic sensor module HC-SR04
2.	1 KΩ resistor 
3.	Arduino Uno 
4.	USB Interfacing cable 
5.	Connecting wires 


### THEORY: 
The HC-SR04 ultrasonic sensor uses SONAR to determine the distance of an object just like the bats do. It offers excellent non-contact range detection with high accuracy and stable readings in an easy-to-use package from 2 cm to 400 cm or 1” to 13 feet.

The operation is not affected by sunlight or black material, although acoustically, soft materials like cloth can be difficult to detect. It comes complete with ultrasonic transmitter and receiver module.
Technical Specifications
Power Supply − +5V DC
Quiescent Current − <2mA
Working Current − 15mA
Effectual Angle − <15°
Ranging Distance − 2cm – 400 cm/1″ – 13ft
Resolution − 0.3 cm
Measuring Angle − 30 degree

The ultrasonic sensor uses sonar to determine the distance to an object. Here’s what happens:

The ultrasound transmitter (trig pin) emits a high-frequency sound (40 kHz).
The sound travels through the air. If it finds an object, it bounces back to the module.
The ultrasound receiver (echo pin) receives the reflected sound (echo).
The time between the transmission and reception of the signal allows us to calculate the distance to an object. This is possible because we know the sound’s velocity in the air. Here’s the formula:

distance to an object = ((speed of sound in the air)*time)/2
speed of sound in the air at 20ºC (68ºF) = 343m/s

### FIGURE 01 CIRCUIT OF INTERFACING ULTRASONIC SENSOR 


![image](https://user-images.githubusercontent.com/36288975/166430594-5adb4ca9-5a42-4781-a7e6-7236b3766a85.png)



### PROCEDURE:
1.	Connect the circuit as per the circuit diagram 
2.	Connect the board to your computer via the USB cable.
3.	If needed, install the drivers.
4.	Launch the Arduino IDE.
5.	Select the board (If you the board is arduino uno, select accordingly).
6.	Select your serial port, accordingly ( E.g. COM5 )
7.	Open the file of the program  and verify the error , clear if any errors that are existing 
8.	Upload the program and check for the physical working. 
9.	Ensure safety before powering up the device 
10.	Plot the graph for the output voltage vs the resistance 


### PROGRAM 
![Screenshot 2024-03-08 192134](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/be8d8fd4-0d30-4d2a-be23-b6c33d603441)
![Screenshot 2024-03-08 192200](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/a7070244-d138-4bf4-9eb7-75e15f6b5685)
### Distance vs measurement table 
![Screenshot 2024-03-08 162109](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/598e6430-8a6b-47e1-b9f9-ff5d9e6b4489)
## GRAPH
![Screenshot 2024-03-08 162124](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/af0ae5b6-9701-4514-9730-c7612051099f)
Average error = sum/ number of readings 
 ## output
 ## LED OFF:
![Screenshot 2024-03-08 160759](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/3c94484b-dfbe-42b7-9162-60c87f3ac5e6)
## LED ON:
![Screenshot 2024-03-08 162333](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/c6a41678-b89f-44fd-ba6e-5c005dd85e06)

![Screenshot 2024-03-08 191958](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/8242c395-d175-4100-be1f-1a7677f10691)

![Screenshot 2024-03-08 193141](https://github.com/Narmadhasree48/Experiment--04-Interfacing-digital-output-with-arduino-ultrasonic-sensor/assets/144979451/0e151a70-2c2f-4ea4-9f53-99c5dba25707)

### RESULTS:
Thus the distance value is measured in "CM" using ultrasonic sensor.



 
