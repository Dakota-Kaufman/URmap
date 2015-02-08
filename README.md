# URmap
University of Regina Interactive Campus Map

Group: Mathew Wilkie, Tyler Foraie, Landon Goodtrack, Sean Wolfe, Dakota, Kaufman
CS 372: Software Engineering Methodology
February 6th 2015
University of Regina Interactive Map Mobile Application
Problem statement: The problem our group project aims to resolve is related to finding your classes
throughout campus. Often times, as new students, and even as veteran University of Regina students
awkward classroom number systems can cause confusion. Furthermore, the maps of the building are
often available, but in a continually digital world a mobile version of the maps would be beneficial.
Allowing students to plan routes, find where their classes are in advanced, and easily find outlying
naming conventions like the "AUD" labeled classes for example. Users will be able to input a class
name in a form such as "CL300" or CL 300" and marker will be placed on the map. A general campus
map will be provided, and upon zooming in, a detailed map of the buildings. A user will also be able to
see their own current location if they are on campus, and potentially direction instructions provided to
the user. This will Android using Java and a three tier user, server, database architecture. The Server
back end will be written in PHP and our database will be MySQL.
Most important features: A view-able map, markers located your classroom on a map, user friendly
GUI.
Functional Requirements
User:
Application is opened: Map will be displayed, with an accompanied text entry bar
User's Location displayed on the map with marker
Enters room number: User Types room number into a text bar such as CL 105
Marker placed: A marker is placed on the map indicating the location of the class
Floor+,up/-,down button pressed: Displayed all buildings in next available floor mode
For user to view classes not on primary floor. Floor indicated in top of app.
Possibly:
User selects get directions: A button may be pressed for directions to be displayed on the
map
Directions displayed: Path laid out on map for user to follow to classroom
Functional requirements for admins:
None: All back enter data entry will be done via SQL scripts. No admin panel on the application
Quality requirements:
Correctness:
Marks correct corresponding classroom location on the map
Marks correct position for users current position (allowing for GPS inaccuracy)
Displays correct floor for classroom location
Possibly:
Gives correct directions to class, without going through walls
Robustness:
Will tolerate non-existing classrooms
Will tolerate incorrect entry format
Will tolerate odd classroom locations like the decimal rooms on campus
Will prevent SQL injection
Performance:
Will display class location quickly
Will update user location in real time
Will be responsive to zooming in and out
Will display floors quickly
Map will load quickly
Possibly:
Will display and update directions in real time
