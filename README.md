# LinkIt7697-BLE-Car
RC Car with LinkIt 7697 BLE function

This piece of code works with pre-existing RC-Car controlling APP that pair with
BLE module that has SPP-Like function. The APP can be downloaded from Play Store
as well as App Store when searching with "PowerTech."

Standalone BLE module has SPP-Like function with service FFE0 and characteristic
FFE1. Therefore it is only necessary to modify the example code from LinkIt 7697
and add the corresponding motor control commands.

The code parse byte command and maps to voltage signals of pin 6 through 13, which
then can be used to control motor, and hence a car, with motor driving module such
as L9110.

Demo video: https://youtu.be/mwG4ibySvww
