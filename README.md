# RoboCity
RoboCity, is a hobby project focused on simulating robotic systems. This project is in the early stages. However, as future works, it should be possible to add more robots or make them custom. Various sensors and modules can be used in simulation. The possibility of writing and installing different software on each robot can be included. Add different steps to the simulator, to learn how to use each dynamic module in their own system, how to perform tasks collectively, how to know the environment and share information among themselves. A person should be able to plan them accurately. Like "go to point one and then rotate exactly 10 degrees" or do this with higher level commands like "pick up the red boxes and then place them on the table in order of size". 

## Robots of RoboCity
HRobot V2 (Not simulated yet)
![](/Documents/Screenshots/HRobotV2.png)
ARobot
![](/Documents/Screenshots/ARobot.png)

## RoboCity Simulator V0.4
Now we are able to make our customized robots
![](/Documents/Screenshots/V4.png)
![](/Documents/Screenshots/V4_RoboCity.png)

## RoboCity Simulator V0.3
![](/Documents/Screenshots/V3_PointCloud.png)


## TODO
- [x] Try to design first sketch of robocity
- [ ] Reimport all Grobots with new JSON structure and RobotGenerator module 
- [ ] Reimport ARobot and HRobot with new JSON structure and RobotGenerator module
- [ ] Make scenes available with socket io on all tabs

## RoboCity Modules
- [ ] Simulator
- [ ] Assistant
- [ ] OS
- [ ] RDK (Robot Dev Kit)
- [ ] Robot Designer
- [ ] Robot App Store
- [ ] MMO World

## RuX SRS Sensors
A list of sensors needs to be implemented
- General
    - [ ] Accelerometer
    - [ ] Camera
    - [ ] ForceTorque
    - [ ] Pressure
    - [ ] Sound
- Light
    - [ ] Photoresistor
    - [ ] Photovoltaic
- Navigation
    - [ ] GPS
    - [ ] Gyroscope
    - [ ] IMU
    - [ ] LiDAR
- Proximity
    - [ ] Contact
    - [ ] Infrared
    - [ ] Ultrasonic
- Thermal
    - [ ] Temperature


## Instruction
- To run project
    - Open 2 terminals in program root and run these command in each
    - `npm run dev`
    - `npm run start-react`

