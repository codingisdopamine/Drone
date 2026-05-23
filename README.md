# Drone
Code for Drone. We are essentially designing the 'brain' of the drone, causing precise flight actions and creating autonomous navigation. 

## things we need to remember
>> especially if we want this to go well.

- using PlatformIO on VSCode for the ESP32-S3
- Private working repo is gonna be set out from there.
- Heavy RAM usage from onboard video compression - Remember to use the microcontrollers external PSRAM.
- PlatformIO is C++, when using the flight controller, it will be PID debugging n sensor fusion in Python cause idk Matlab yet.
- For the flight controller, we r using **Betaflight Configurator**,  should be easy as long as we give it time to work. 
