## Software_Design_

# Product Requirements Document
Overview:
Real-time truck and fleet tracking platform designed for enterprises managing vehicle fleets. The product combines GPS hardware, web dashboard to provide live location tracking and driver safety monitoring. 
This system supports both normal and specialised vehicles (refrigerated, tanker) through optional sensor integration.

Understand the Problem:
The truck company owner has a few issues that we can solve.
- He doesn't know real time location of his trucks,
which results into unexpected delays and no control over the transportation process.
- Little to no safety against highjackers/thieves.
- No driver's behaviour data (harsh braking, acceleration)
- Cargo volume/weight monitoring
- Temperature control for specific goods

What is the system doing?
- The system must safely and promptly send the acurate location of each truck.
- The system must support geofencing, triggered at a certain range.
-  The reciving side must get a report on driver's driving style ( trigger harsh moves ).
- Reciving side will also get any temperature and change in weight flags.

Scope:
In Scope
- Real-time GPS tracking
-	Geofencing 
-	Web-based fleet dashboard live map
-	Driver behaviour (accelerometer)
-	Temperature monitoring
Out of scope
-	Video cameras for Driver’s behaviour
-	Fuel consumption monitoring 
-	Service history
Functional Requirements
-	Display the current location of every active vehicle on a map
-	Off shift tracks trigger geofencing 
-	 Temperature alerts
-	Accelerometer should detect harsh braking, rapid acceleration
Non-Functional Requirements
-	The platform should handle the load
-	The device must fit any type of trucks 
- The driver should not have direct access to the device 
-	Device must me humidity/temperature immune 


This diagram outlines the core requirements for the Truck tracking system:
<img width="1072" height="457" alt="Screenshot 2026-11-05 212359" src="https://github.com/user-attachments/assets/9f4b3192-4fea-4583-adf6-15250df22804" />
Also a representation through use cases:
<img width="857" height="602" alt="image" src="https://github.com/user-attachments/assets/d545f841-a662-4d12-b80c-3935dfad2528" />
