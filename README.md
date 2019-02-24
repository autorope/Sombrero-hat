# Sombrero-hat
This is the board files for the Sombrero hat.  The Sombrero hat should just work with the most recent donkey software, however if you are hacking on it. The following Pins will matter to you:

PMW OUT (0-5) - PCA Channel 2-7

I2C.SDA - BCM[0]
I2C.SCL - BCM[1]
LED.0 - BCM[13]
LED.2 - BCM[19]
GPIO.0 - BCM[16]
GPIO.1 - BCM[20]
GPIO.2 - BCM[21]
Enable BCM [26]

The most important one, is that the hat has an enable pin - this has to be pulled low in order for the car to work.  This is always a nice feature for all robots as it can act as a kill switch.  The LEDs need to be driven low as well in order to work. 

For more information on the hat watch this [video](https://youtu.be/vuAXdrtNjpk)
