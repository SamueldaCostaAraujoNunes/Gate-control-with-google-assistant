# Gate control with Google Assistant and Sinric :door:
## Project description
<p align="justify"> A project for the Arduino Leonardo, interested in automating the rotation of the orientation of the computer screen, using an MPU-6050 gyroscope. </p>


### Motivation:
When I started programming, I felt the need for a secondary monitor to help me develop programs. Today, I can no longer live using just one monitor. Generally, I use one monitor vertically (where the IDE is located, texts, articles, documentation), and the other is free for auxiliary needs. In my spare time, I rotate the monitor, and use it to watch different media. Over time, I started to see how repetitive the process of changing the screen orientation is. So, I decided to make things a little more automated :sunglasses:.

### What you will need:
 - 1 Arduino from the Leonardo family. (I used the micro pro, but either one works)      
 - 1 GY-521 MPU-6050 sensor      

### Schematic 
 ![Esquema](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/Schematic.png)
 
 
### How it works
An Leonardo arduino will be connected to a gyroscope / accelerometer, and when there is a change in the orientation of the sensor, the arduino will send a keyboard shortcut to the computer to change the direction of the screen.

### Results

  MPU-6050 sensor in television :exclamation:
  
 ![Sensor](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/GateBoard.png)
 
  Arduino Leonardo Pro Micro :exclamation:
  
 ![Leonardo](https://github.com/SamueldaCostaAraujoNunes/Automatic-monitor-rotation/blob/master/src/leonardo-pro-micro.jpg)
 
 Results :exclamation:
 
 ![gif](https://github.com/SamueldaCostaAraujoNunes/Automatic-monitor-rotation/blob/master/src/rotation-gif.gif)
 
### Used libraries :books:
 - [MPU6050_tockn](https://github.com/tockn/MPU6050_tockn)
 
### Project status
 > Project status: Always in development :sweat_smile:
