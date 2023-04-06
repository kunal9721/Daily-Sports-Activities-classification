# Daily-Sports-Activities-classification

Daily sports activities (UCI) consist of 19 exercises conducted for 5 minutes by eight subjects (four females and four males between the ages of 20 and 30). The total signal duration for each subject's activity is 5 minutes.
The subjects were invited to perform the exercises in their own unique style and were not restricted in any way. As a result, the speeds and amplitudes of various activities differ amongst subjects. This is a multi-classification problem where we are classifying the person performing which of the following activities.
The 19 activities are:
“Sitting (A1),
standing (A2),
lying on back and on right side (A3 and A4),
ascending and descending stairs (A5 and A6),
standing in an elevator still (A7)
and moving around in an elevator (A8),
walking in a parking lot (A9),
walking on a treadmill with a speed of 4 km/h (in flat and 15 deg inclined positions) (A1
0 and A11),
running on a treadmill with a speed of 8 km/h (A12),
exercising on a stepper (A13),
exercising on a cross trainer (A14),
cycling on an exercise bike in horizontal and vertical positions (A15 and A16),
rowing (A17),
jumping (A18),
and playing basketball (A19)”.

Data Structure: As per UCI “the dataset comprises motion sensor data of 19 daily and sports activities each performed by 8 subjects in their own style for 5 minutes. Five Xsens MTx units are used on the torso, arms, and legs
19 activities (a)
8 subjects (p) 
60 segments (s) 
5 units on torso (T), right arm (RA), left arm (LA), right leg (RL), left leg (LL) 
9 sensors on each unit (x,y,z accelerometers, x,y,z gyroscopes, x,y,z magnetometers) 

Folders a01, a02, ..., a19 contain data recorded from the 19 activities. 
For each activity, the subfolders p1, p2, ..., p8 contain data from each of the 8 subjects. 
In each subfolder, there are 60 text files s01, s02, ..., s60, one for each segment. 
Columns 1-45 correspond to: 
T_xacc, T_yacc, T_zacc, T_xgyro, ..., T_ymag, T_zmag, RA_xacc, RA_yacc, RA_zacc, RA_xgyro, ..., RA_ymag, RA_zmag, LA_xacc, LA_yacc, LA_zacc, LA_xgyro, ..., LA_ymag, LA_zmag, RL_xacc, RL_yacc, RL_zacc, RL_xgyro, ..., RL_ymag, RL_zmag, LL_xacc, LL_yacc, LL_zacc, LL_xgyro, ..., LL_ymag, LL_zmag. 
Therefore, 
columns 1-9 correspond to the sensors in unit 1 (T), 
columns 10-18 correspond to the sensors in unit 2 (RA), 
columns 19-27 correspond to the sensors in unit 3 (LA), 
columns 28-36 correspond to the sensors in unit 4 (RL), 
columns 37-45 correspond to the sensors in unit 5 (LL),”


Refer to 
