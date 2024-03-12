# mars_rover
DIY Mars Perseverance Rover Replica project. Inspired by the real rover currently exploring Mars, this project allows enthusiasts, students, makers, and robotics enthusiasts to build their own Mars rover

**Main Features:**
1. Rocker-Bogie Suspension: The replica employs a rocker-bogie suspension system, similar to the real Mars rovers. This design allows the rover to smoothly traverse uneven terrain and climb obstacles (such as rocks) up to twice the wheel’s diameter while keeping all six wheels in contact with the ground.
2. Individual Wheel Motors: Each wheel has an independent DC motor for forward and backward movement.
3. Ackermann Steering Geometry: To efficiently steer the rover and prevent tire slipping during turns, the project implements Ackermann steering geometry. This ensures that inner steering wheels have a greater angle and slower speeds compared to outer wheels during turns.
4. Brain: Surprisingly, the brain of this Mars rover is an Arduino MEGA board. A custom PCB simplifies connections between components and the Arduino board.
5. FPV Camera: The rover features an FPV (First-Person View) camera controlled by stepper and servo motors. Real-time video is transmitted to a smartphone.
6. Appearance: While some parts are non-functional, they match the appearance of the real rover. The robotic arm is missing in this version, but future enhancements are planned.
