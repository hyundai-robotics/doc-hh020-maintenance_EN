# 6.5. Encoder Zero Setting 

It is necessary to reset the origin when encoder data has been corrupted due to some problems and when the motor is replaced.

Scale is used for deciding the location of the reference position of each axis of the robot. When the user replaces the motor, set the encoder using the scale to set the zero point of each axis.




![](../../_assets/작은주의표시.png) <b>Warning</b>

In this work, there is a part performing in the state of motor [ON]. Therefore, this work must be performed in pairs. One must always be ready to activate an emergency stop. The other must perform the work quickly but carefully. 
An escape route should be determined before starting work.
