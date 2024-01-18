# traffic-speed-estimation
I have used YOLO v8 for vehicle detection

Used  ultralytics.solutions.object_counter for counting the number of vehicles comes IN and OUT using a reference line.

Used ultralytics.solutions.speed_estimation for calculating the speed of the vehicle entering the reference line.

Speed estimation uses ByteTracker algorithm.

I have got small values as speed since I have run it on a CPU machine. Using a high end system will give more accurate results.

This object counting can be used in various application like 
1. counting the objects coming through conveyor belts (in manufacturing industry)
2. shopping store monitoring. We can count the persons coming IN and OUT of the market and can manage the crowd more effectively
3. We can also track the customers in the supermarket  whic will improve security.
4. Even we can speedup the billing procedure if we tract the customer and make a list of the things he/she took.
And many more!
