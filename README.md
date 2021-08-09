# Door_Motion_Control_System_using_Arduino

This is a simple example of security system that allows access to the place to only authorized people.
It uses an Arduino UNO R3 board which is connected to various peripherals listed below:
1) Mini servo motor
2) 4x4 matrix keypad
3) Led
4) Buzzer
5) 16x2 LCD display

The system accepts the user input as a pin from the keypad and compares it with the saved password that is saved in memory of Arduino.
If the password is correct, then the door is opened for the user for 8 seconds and then closes automatically to let the user in.
If the password is incorrect, then the buzzer is sounded indicating an alert or intruder detection near the protected area.

In this way the door access is controlled in a simple manner.

In real life application, the servo motor can be chosen according to the door size and weight in order to drive it.
The driver for the motor will also be required as arduino cannot drive such huge motors.
We can use amplifier circuit in between in order to control the motion of the servo motor.
The keypad and display will remain as it is and will contain in a single unit resembling into integrated system.
