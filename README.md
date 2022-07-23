# Automatic-Number-Plate-Detection

* Problem Statement: In this challenge, the participant needs to build a robust automatic number plate recognition system that can detect moving vehicles in real-time traffic and extract the number plate (license plate) of the vehicles from multiple cameras (minimum 3 cameras).
![image](https://user-images.githubusercontent.com/95335025/180599651-ed9cae3b-8524-46b1-b7bd-178eadf48fe6.png)

* Vehicle Types: - 1. Bus 2. Truck 3. Bike 4. Car 5. Auto Rickshaw

* Vehicle class types: - 1. Commercial vehicle (Yellow number Plate)
                         2. Private vehicle (White Number Plate)
                         3. Rented/hired (Black Plate)

* Camera Setups: - Distance of vehicle should be a minimum 5-10 meters from the camera

* Detection Constraints: - 1.	Detect the vehicle moving at a speed of 0-30 km/hr.
                           2.	Detect the license plate of the vehicle.
                           3.	Detect the vehicle type and the license plate type (commercial/personal etc.).
                           4.	Extract the number from the license plate.
                           5.	Detect if the vehicle is stationary or gauze the speed of the moving vehicle.
                           6.	Records to be kept with date, time, vehicle types, vehicle class, and camera number (the camera that has detected the vehicle) in one                                   table in a single database (any NOSQL database).
                           7.	Minimum 5-meter distance should be maintained from the camera.


* Calculations to be Achieved and shown within the frame: - 1. Total vehicle count
                                                            2. Total extracted number plate count
                                                            3. Category count for each vehicle type
                                                            4. Add date and time stamps for the detection of each vehicle type

* Dataset:
The participant needs to collect their own real-time dataset or can use it from the internet if available according to the requirements of the challenge. 
The dataset should also contain images in different lighting conditions like morning, afternoon, evening, and night.

* Metrics to be achieved: -
     1.	Accuracy 90%
     2.	At least 15 frames per second


