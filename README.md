# University Residence Management System

## Objectives

- Apply Object-Oriented Programming (OOP) concepts in JavaScript
- Model and design classes for managing university residences

## Details of the implementation

1. Residence Class:

   Base class for DormRoom and Apartment.
   Contains common properties such as name, address, and isOccupied.

2. DormRoom Class:

   Inherits from Residence.
   Adds size property.
   Method calculateRent calculates rent based on the size of the room.

3. Apartment Class:

   Inherits from Residence.
   Adds bedrooms property.
   Method calculateRent calculates rent based on the number of bedrooms.

4. Student Class:

   Contains properties like name, studentId, gender, and residence.
   Method assignResidence assigns a residence to the student and sets the residence as occupied.

5. MaintenanceRequest Class:

   Contains properties like description, student, status, and employee.
   Methods to update the status of the request and assign an employee.
