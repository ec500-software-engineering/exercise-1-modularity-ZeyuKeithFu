# exercise-1-modularity
## System diagram
Credit to [Miguel Mark](https://github.com/mmark9/ec500_spring19_misc)
![](https://github.com/mmark9/ec500_spring19_misc/blob/master/ec500_heart_monitor_diagram.png)

## Usage
By running ```main.py```, the health monitor system will start working and display the following messages.
```
< 88 bps HEART RATE > | < 0/0 SYS/DIA mmHg kPa > | < 0% Oxygen Saturation >
< 85 bps HEART RATE > | < 0/0 SYS/DIA mmHg kPa > | < 0% Oxygen Saturation >
< 85 bps HEART RATE > | < 134/58 SYS/DIA mmHg kPa > | < 0% Oxygen Saturation >
< 99 bps HEART RATE > | < 134/58 SYS/DIA mmHg kPa > | < 0% Oxygen Saturation >
< 99 bps HEART RATE > | < 134/58 SYS/DIA mmHg kPa > | < 13% Oxygen Saturation >
< 55 bps HEART RATE > | < 134/58 SYS/DIA mmHg kPa > | < 13% Oxygen Saturation >
< 55 bps HEART RATE > | < 94/83 SYS/DIA mmHg kPa > | < 13% Oxygen Saturation >
sms> TO: Nurse Suzy
		!!!! PATIENT ALERT BLOOD PRESSURE ABNORMAL !!!!
telegram>> BOT > TO: Nurse Suzy
		!!!! PATIENT ALERT BLOOD PRESSURE ABNORMAL !!!!
< 68 bps HEART RATE > | < 94/83 SYS/DIA mmHg kPa > | < 13% Oxygen Saturation >
< 67 bps HEART RATE > | < 94/83 SYS/DIA mmHg kPa > | < 13% Oxygen Saturation >
```
The system reads pulse, blood pressure and blood Oxygen. Once it detected abnormal numbers, alert message will be sent.
