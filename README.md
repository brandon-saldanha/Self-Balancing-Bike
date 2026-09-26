# Self-Balancing-Bike

Arduino nano, Nidec 24H motors, BLDC motors, MPU6050, 3S 1000 mAh LiPo battery.

Balancing controller was tuned remotely over Bluetooth.

Example (change K1):

Send p+ (or p+p+p+p+p+p+p+) for increase K1.

Send p- (or p-p-p-p-p-p-p-) for decrease K1.

Remote control via the Joy BT Commander app.


<img src="/pictures/schematic.png" alt="Schematic"/>

About the schematic:

Battery: 3S1P LiPo (11.1V 500-1200mAh). 

Buzzer: any 5V active buzzer.

Transistor: 2N2222 or similar.

Servo: TowerPro MG995 or similar size.

The voltage regulator 7805 is not the best choice. Use any 5V switch type small regulator.


## Credits & Acknowledgments
* This project was built following the implementation/tutorial by remrc.
* Primary modifications made: BLDC motor model and rating, weights on the bike, the motor controller. 
