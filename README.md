# Parking-Assignment
This is a low level menu driven parking lot management design.
I have used object oriented design in order to develop the application.
Requirements
1.Parking Lot
2. Type of vehicle
3 No. of empty slots
4.Fee for different types of vehicles
5.Total Revenue collected.

As this is a low level design i have used a single class Vehicle with data memmbers
    string pltno;
    int type;
    date dt;
    time arrive;
    time departure;
And Member functions
    void addVehicle();
    void deleteVehicle();
    void printvehicle(vehicle v);
    void show();
   
pltno is the vehicle plate Number which is used to uniquely identify a vehicle
dt is a varibale of type date which is a user-defined struture
time arrive and time departure are varibakes of data type time whichs again user-defined

addVehicle() is used to add vehicle to the parking lot it is called whenever a new vehicle enters.
 This function will take the type of vehicle entering and at what time it enters and it will keeptrack of the vehicle using the pltno.
 It will set the data members of that instance to the entered value.
deleteVehicle() is used whenevr a vehicle leaves the lot this function will take plno and departure time as input and pltno

printVehicle() will display all the vehiles parked in the lot with arrive time and pltno

We have 2 external functions totalVehicle() which will show the total number of cars and total number of bikes
totalCollection() will show the total colletion for that day.

In the main() function we have a menu which will help the admin.
    
