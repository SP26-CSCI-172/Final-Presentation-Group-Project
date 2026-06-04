# Final-Presentation-Group-Project-MACHINEMINDS
## MACHINE MINDS Final Project

### Problem Statement
We need a guard dog to help protect our home. Actual guard dogs are expensive and fall asleep on the job, so we decided to build one! Our robot will be able to **patrol** a specified doorway space, **detect "threats"** based on passing movement, and **"attack"** these threats. The robot will follow a line which will prevent our robot from wandering. Our robot guard dog will know several stages of defense, controlled by a remote. 

### Sensors
- **IR line tracking sensor**: Allows us to contain the robot in a contained patroling area. This also allows us to easily change the patrol path.
- **PIR sensor**: Identify intruders to chase. If the PIR sensors detects something close enough, it will go towards the object, scaring it away.
- **IR remote sensor**: Used to select the mode that is desired.
- **Ultrasonic sensor**: Identify objects when patrolling.

### Code Overview
The code has several parts;First of all we define all of the pins and variables we will need. Next, we declare and define all of the functions we are going to use in the loop. After that we have a switch/case in the loop function that will call the different functions depending on the button pressed on the IR Remote.

### Innovations
Robot that follows the line and turns around when it gets to the end of the path. It also detects objects and attacks.

### Challenges & Solutions
A challenged we faced is the buzzer not working. It was interrupting our previous code and made the remote stop functioning. We also struggled to get the line tracker to work. We were able to stick to our initial design, but without the buzzer. If given more time, we would have fixed the buzzer.

### Member Contributions
Lili: frame-building, coding, troubleshooting, etc.
Lincoln: frame-building, coding, troubleshooting, etc.
Noa: frame-building, slideshow creation, etc.
Evan: wiring, slideshow
Ben: frame-building, slideshow
Jaxon: troubleshooting, slideshow creation

### Instructions for Running the Robot
Load the code and turn on the robot. Select mode with IR Remote. Press 1 if you want the robot to patrol and follow the path, press 2 if you want the robot to go into attack mode. Press 3 for the robot to stop.
