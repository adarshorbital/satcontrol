# satcontrol
Activity for determining and controlling attitude of satellite using Arduino

This activity makes use of an Arduino Mega as a microcontroller in order to determine attitude and control the angular motion of an actuator. The idea is to provide students with a physical hardware where they can test their attitude determination and control algorithm and realize that what works in simulation may not work when implemented on actual hardware. 

This activity allows students to create their own attitude determination and control algorithms on MATLAB and Simulink and then testing it out on Arduino based physical hardware to determine if their algorithms work in the real world. 

Students need to be senior undergrads or graduate students to involve in this activity. An introduction of this activity can be given in a classroom, but students are supposed to work on it themselves and test out their code with the hardware. Two weeks should be given for students to work on this, given the fact that they have the basics of attitude determination, Kalman filtering and controls. The student needs to have intermediate level understanding of MATLAB and Simulink, with some experience with prior coding in the language. Generally, students who are involved in this activity are offered to do this as a group assignment in the course where they are given a quick demo of how the setup works, after which they can think about designing their own code. It can be adapted into other settings with proper planning and ideas if the vision of the activity is clear enough. 


This activity makes use of an Arduino Mega as a microcontroller in order to determine attitude and control the angular motion of an actuator. Students get to understand how attitude determination actually works, how filtering works in context of electronics and how hardware control execution is done. The idea is to provide students with a physical hardware where they can test their attitude determination and control algorithm and realize that what works in simulation may not work when implemented on actual hardware. MATLAB and Simulink is used for the coding of the program which is them uploaded to Arduino. Students need to think about how Simulink blocks come together and work with MATLAB for execution to take place. They need to understand the interface between the hardware and software and how data acquisiton and control takes place. It uses critical thinking and model development techniques.  This can further be used by students to give a quick 5 minute overview of what they achieved as a result of working on this activity. 

The instructor needs to download the CAD files and then use a 3D printer to print out the designs. They also need a breadboard, jumper wires, stepper motor, Arduino Mega, MPU6050. 
This activity is currently being uploaded on github for better visibility. 

https://github.com/adarshorbital/satcontrol


Students can be assessed on the fact that how accurately they were able to find the current angle of their IMU (pitch) and how accurately they were able to control the actuator to move it to the appropriate angle. They can be assessed on the error in between the desired value of pitch and the pitch obtained during the determination and control activity.  
