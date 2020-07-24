# ArduinoMezzo
Arduino Mezzo is a functional half-scale replica of the Arduino Uno.<p/> 
![My image](https://raw.githubusercontent.com/tseary/ArduinoMezzo/master/images/Arduino%20Mezzo%20v1%20top.png)<p/>

I created this project as a novelty and as an exercise in miniaturization. As much as possible, the components
are 50% of the size of the components on the real Uno. The pin headers are all 50 mil pitch instead of 100 mil, and
the LEDs are 0402's instead of 0805's. Some parts differ because a half-scale version doesn't exist - the
USB connector is a mini-B instead of B type, and the power jack is has a 2.5 mm OD instead of the standard 5.5 mm.<p/>

Functional differences include a simplified power supply, and a different chip entirely for the USB-serial bridge.
The real Uno power supply has comparators and MOSFETs to select between USB and battery power. The Mezzo simply
combines the two sources using schottky diodes. To program the Mezzo, you have to manually press the reset button
since there is no DTR reset as in the Uno.<p/>

I hope that this project amuses you as much as it did me. If you make your own Mezzo I'd love to see it!<p/>

Disclaimer: This is not an official Arduino product and I am not affiliated with Arduino in any way.
This design is made available for anyone to use for any purpose, at their own risk.
