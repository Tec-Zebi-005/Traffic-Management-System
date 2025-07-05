The Traffic Management System is a C++ desktop application for managing vehicles,
 traffic violations, challans (fines), and a 4-way traffic signal simulation. Key features include:

User Management: Register/login as Admin or User, with data stored in users.txt.
Vehicle Management (Admin): Add Car, Bike, or Ambulance details (owner, direction, speed, ID) and save to vehicles.txt.
Violation Tracking (Admin): Check speed/direction violations, store in violations.txt.
Challan Management: Admins issue challans with fines (Bike: 300 PKR, Car: 500 PKR per violation);
Users view their challans, stored in challans.txt.
Traffic Flow Simulation: Displays a 40-second cycle of traffic signals (10 seconds per direction), stoppable with 'q'.
The system uses text files for data storage, is Windows-specific, and supports role-based access.
