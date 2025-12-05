# Calibrate-Your-SwiftBot
This project is to measure the speed of the SwiftBot since we can't use the traditional formula (Speed = Distance / Time).
The SwiftBot travels in terms of percentages. For example "bot.move(20, 20, 2000)" would be 20% of the SwiftBot's max speed.
We like to move the robot in seconds but the robot is in milliseconds, so however long we want the robot to travel for, we must times the seconds to 1000 to get to milliseconds. (seconds * 1000 = milliseconds).
