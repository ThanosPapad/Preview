# Preview of Autopilot Project

The design architecture changed.

AutopilotV0 has the STMF103RBT6 as the main MCU, uses the SIM28 GPS module, ST's LSM6DSO and LSMDSRTR as IMUs, LP522HBTR atmospheric pressure and exposes 5 PWM channels for motor control.

AutopilotV1 has the STMF103RBT6 as the main MCU too, but it uses ST's TESEO-LIV3F GPS module, which has much better accuracy, also it uses Bosch's BNO055 IMU which calculates roll, pitch and yaw on chip.

You can find the schematics for both as well as some pictures of the hardware. 

AutopilotV1 is in development so it's not very pretty.

The firmware you will find in the repo is for the AutopilotV1 hardware and It's also in the very early stages.
