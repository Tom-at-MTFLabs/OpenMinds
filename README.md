# OpenMinds
This is the code repository for the OpenMinds toolkit.

For a how-to guide, head here: https://github.com/Tom-at-MTFLabs/OpenMinds/blob/main/How%20to%20use.txt


![OpenMindsBoard](https://github.com/Tom-at-MTFLabs/OpenMinds/assets/132015606/89fb9806-1b30-472b-8e1a-9bd47956cfe2)

This breakout board is based on the Raspberry-Pi Pico W board, a microcontroller that can read information from sensors to input data and also control outputs such as motors, lights, speakers. The idea for this board is to try to make it easy to use the inputs to control the outputs. 

For example, there is a light sensor built into the board which can control outputs depending on how much light is hitting it. Using some code, you could control the colour of the RGB light, or the position of a servo motor, or the frequency of a speaker. Or even send that information to a webpage and display the information there. 

The board has a light sensor and a button as its built-in inputs. But has 2 connectors which can connect to a huge range of sensors from the Grove series of i2c sensors. We have included some example code for a few of those, such as the distance sensor.

The board has a few onboard outputs too. There is a simple speaker, for playing tones and frequencies. There is a RGB LED that can change colour and brightness. There is a haptic-motor that can vibrate the board much like a mobile phones vibration feature. There is a connector that allows easy use of a Servo Motor. This special type of motor allows you to control the exact position of the shaft of the motor to either a specific angle or, if using a continuous servo, the exact speed and direction of the motor. The i2c connectors also allow you to connect a whole range of outputs too! We have tested parts from the Grove range again and were able to control things like tiny OLED screens.

The Pico W also has tons of additional pins to connect additional things to, so we have included crocodile clip compatible connections for you to access those should you need it.



Connections and pins include:

Haptic Motor : GP11

Neopixel LED : GP00

Button: GP22

LDR: GP26

Speaker: GP21

i2c 1 connector: SDA - GP14  -  SCL - GP15

i2c 0 connector: SDA - GP16  -  SCL - GP17

Servo Connector - GP18


