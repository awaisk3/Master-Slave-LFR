# Master-Slave-LFR
This projects involves two robots, a Master Robot, and a Slave Robot, implemented using Arduino UNO-R3. The Master Robot uses two IR sensors for line detection and an Ultrasonic sensor to detect obstacles. Additionally, the IR sensors are utilized as Transmitter and Receiver to enable communication between the Master and Slave Robots, allowing the Slave Robot to follow the actions of the Master Robot.

Here's an overview of how the project will work:

1. Master Robot:
   - Line detection: The Master Robot uses two IR sensors to follow a line or track on the ground. The IR sensors can detect the contrast between the line and the surrounding surface, enabling the robot to stay on the designated path.
   - Obstacle detection: The Master Robot uses an Ultrasonic sensor to detect obstacles in its path. The Ultrasonic sensor emits sound waves and measures the time it takes for them to bounce back after hitting an obstacle. This data is used to calculate the distance to the obstacle, allowing the robot to avoid collisions.
   - Master-Slave communication: The IR sensors on the Master Robot are used as a communication interface between the two robots. By modulating and transmitting IR signals, the Master Robot can send specific commands or instructions to the Slave Robot.

2. Slave Robot:
   - Follow Master: The Slave Robot receives commands from the Master Robot through the IR communication. It interprets the received signals and performs actions accordingly, following the movements and instructions of the Master Robot. For example, if the Master Robot turns left, the Slave Robot will also turn left to mimic its actions.

Overall, the Master Robot acts as the leader, navigating the path and detecting obstacles, while the Slave Robot acts as the follower, replicating the movements and actions of the Master Robot.
