THIS IS A PROJECT TO SOLVE A MAZE USING IR SENSORS MOUNTED ON A MOVING ROBOT

ALGORITHM EXPLANATION
In this algorithm, the robot is instructed to follow a
preference of directions. There may be two sets of sequences of
preference. They are- (1) ‗Left-Front-Right-Down‘ and (2)
‗Right-Front-Left-Down‘. For example, we may mark
directions as follow: (1) for right, (2) for up, (3) for left and (4)
for down. Whenever a junction is encountered, the robot will
always choose a path based on the preference sequence. Let,
there are two paths coming out of one path, one goes to the left,
another to the right. If the robot comes across it, it will first go
to the left path (For sequence 1) to explore it. This junction and
taken direction will be saved in the memory. If after following
the path, it comes to a dead end it will turn back and come to
the previous position. After reaching that position, previously
saved value in the data structure will be extracted and the
present preferred direction number will be added to that value.
This new value will be saved again in the same place of the
data structure. Same procedure will be followed continuously
until it finds the ‗end-point‘. So, the robot will have a record of
number of junctions it came across and a corresponding array
to record the taken direction. Moving like this, one time the
robot will reach the ‗end-point‘ and the recursively updated
direction array will generate an error free simple path from
starting point to finishing point. Here, is an example showing
how it works.

STEPS 
1. INSTALL ADRUINO IDE
2. RUN WHITELINE CODE
3. RUN BLACKLINE CODE
4. TRANSFER THE PROGRAM TO THE ADRUINO BOARD USING COM 13 PORT
5. TEST ON SERIAL MONITOR


