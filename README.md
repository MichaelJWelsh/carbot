# CarBot


This project was created for my Intro to Electrical Engineering class final. All of the electrical components (excluding the Arduino) are old and were found around the class so there were a lot of problems putting everything together and fixing malfunctioning hardware. Regardless, the project was a success. 


CarBot is capable of being driven manually with a simple breadboard controller and supports moving forward/backwards and rotating left/right. It can also use both its ultrasonic sensors to detect objects and print out to the LCD how far away they are. 


CarBot can be changed to autonomous mode via a switch, and the breadboard controller can then be disconnected. In autonomous mode, it utilizes both ultrasonic sensors to detect distance and direction and tries to follow a moving object in front of it. Unfortunately, the ultrasonic sensors were old and cheap, so even after trying multiple different smoothing functions, the readings were often inaccurate and autonomous mode worked somewhat poorly.


[![CarBot](https://github.com/MichaelJWelsh/carbot/blob/master/youtube.png)](https://www.youtube.com/watch?v=_SSJAW3uo78 "CarBot")


