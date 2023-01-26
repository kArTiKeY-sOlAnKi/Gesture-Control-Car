# Gesture-Control-Car

1. In this project a gesture based car was operated with the help of Arduino NANO as microcontroller.

2. Components Used: Accelerometer(MPU 6050), Encoder and Decoder (HT12E and HT12D resp), RF Module, DC gear motors, Motor Drive (L293D) and Arduino NANO.

3. Working Principle of this project is, the coordinates from accelerometer are noted down better to get them in a range. For eg note the value of the coordinates from MPU6050 both x and y coordinates. And follow the similar steps for each direction. And these values are being fed to Arduino NANO which will transmit our data to pair of encoder and decoder in between to ultimately to the motor drive(L293D).

4. Working Principle(contd): L293D uses a H-Bridge Architecture which will respond to our signals and move the DC Motors attached to the wheels of the car respectively.