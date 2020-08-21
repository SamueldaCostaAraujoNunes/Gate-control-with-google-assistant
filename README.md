# Gate control with Google Assistant and Sinric :door:
## Project description
<p align="justify"> A project for Nodemcu, interested in automating the control of a gate, using Sinric and Google Assistant / Home. </p>

### Motivation:
I have always wanted to automate functions and devices in my home, to make their control more dynamic and simple. I found several alternatives on the internet, but none met my needs. To bring all my smart devices together on a single platform, to create different scenes and routines. So, I started using Google home to connect all my devices. To connect the devices I made, I used sinric, which assists in the creation of smart devices using ESP8266 cards, although the platform is very useful, there is only one example of a device that supports Google Assistant, and here we are. This is a Sketch for NODEMCU 1.0 v3, which acts to control a gate, making it a little more intelligent.:sunglasses:.

### What you will need:
 - 1 Nodmcu 1.0 v3.
 - 2 Polarized capacitors 470uF.
 - 2 Capacitors 0.1uF.
 - 1 Voltage regulator LM7805.
 - 1 Diode 1N4001.
 - 1 Relay 12v.
 - 1 Transistor BC547.
 - 1 Resitor 4.7k OHM.
 - 1 Gate control board.

### Schematic 

 ![Esquema](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/Schematic.png)
 
 
### How it works
The gate control boards generally have a separate door for a button (BOT), a power supply for 12v accessories and indication LEDs to indicate the position of the gate. The circuit simulates a click of a button, opening or closing the gate. These boards also have a 12v output, for extra accessories, such as electromagnetic locks ... In this case, I used it to supply the relay and the Nodemcu board. And I used the LED signal to indicate the status of the gate.

Gate controller board doors :exclamation:
 ![Saidas](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/GateBoard.png)

### Results
![PlacaProntaGif](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/GateVideo.gif)

![PlacaPronta](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/PlacaPronta.png)

![FotoDaPlaca](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/ProntoNoPortao.jpeg)

![VideoAbrindo](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/Abrindo.gif)

![VideoFechando](https://github.com/SamueldaCostaAraujoNunes/Gate-control-with-google-assistant/blob/master/src/Fechando.gif)
 
### Used libraries :books:
 - [Sinric](https://github.com/kakopappa/sinric)
 
### Project status
 > Project status: Always in development :sweat_smile:
