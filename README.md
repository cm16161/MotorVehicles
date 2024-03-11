# MotorVehicles

## Challenge: 
Write a command-line program that stores and displays the details of motor vehicles and their associated owners for a Motor Registry. 

A Vehicle has the following details: 
* Type
* Make 
* Model 
* Year 
* VIN
* Rego Number 
* Rego expiry 
* Garage Address 
* Owner Name 

An Owner of a vehicle has the following details: 
* License Number 
* License Class 
* First Name 
* Surname 
* Date of Birth
* Address 
* Phone number 
* Email Address

The command line interface must have a menu that allows the user to:
1. Input Details
    1. Vehicle details
    2. Owner details

2. Display the following details: 
    1. All vehicles sorted by type
    2. All vehicles sorted by make
    3. All vehicles sorted by model
    4. All vehicles sorted by year 
    5. All vehicles sorted by Owner name
    6. Only vehicles with expired rego. 
    7. All owners sorted by Family name.

**Note: A vehicle can have only one owner, but an owner can own many vehicles**

### Stage 1:
Initially, store all information in memory. (Hint: Make use of Structs, linked lists, and doubly linked lists to store and manage this data in memory).

### Stage 2: 
Modify your solution of Stage 1, to allow for storing of information in a file. 
Data can be read from the store and written to facilitating storage of records.
Do not use any libraries/databases for this Stage.
All data must be stored in a flat file and you must come up with the most optimised method to store and retrieve data from the file.

### Stage 3: 
Modify your existing program to transform it into a client/server solution. 
This means the storage file will be stored and interacted with on by a separate service. 
This service may or may not exist on the same system, hence the client is to communicate with the server via a TCP connection. 
It is up to you to determine where the "brains" of this system lives. i.e what functionality do you put in the client side (does it just connect to the server and display results), or do you put more smarts in the client ?
