# OOP Lab Manual

## Week 04

### Experiment 01

Write a class named Employee that has the following member variables:

- Name: A string that holds the employee’s name
- idNumber: An int variable that holds the employee’s ID number
- Department: A string that holds the name of the department where the employee works
- Position: A string that holds the employee’s job title

The class should provide the following constructors:

1. A constructor that accepts the employee’s name, ID number, department, and position as arguments and assigns them to the appropriate member variables.
2. A constructor that accepts the employee’s name and ID number as arguments. The department and position fields should be assigned an empty string ("").
3. A default constructor that assigns empty strings ("") to the name, department, and position member variables, and 0 to the idNumber member variable.

Write appropriate setter and getter functions that store and return the values in these member variables.

Once you have written the class, write a program that creates three Employee objects to hold the required data. The program should store this data in the three objects and then display the data for each employee on the screen.

---

### Experiment 02

Write a Circle class that has the following member variables:

- radius: a double
- pi: a double initialized with the value 3.14159

The class should have the following member functions:

- Default Constructor: A default constructor that sets radius to 0.0
- Constructor: Accepts the radius of the circle as an argument
- setRadius: A mutator function for the radius variable
- getRadius: An accessor function for the radius variable
- getArea: Returns the area of the circle, calculated as:

```text
area = pi * radius * radius
```

- getDiameter: Returns the diameter of the circle, calculated as:

```text
diameter = radius * 2
```

- getCircumference: Returns the circumference of the circle, calculated as:

```text
circumference = 2 * pi * radius
```

Write a program that demonstrates the Circle class by asking the user for the circle’s radius, creating a Circle object, and then reporting the circle’s area, diameter, and circumference.

---

### Experiment 03

Design an Inventory class that can hold information and calculate data for items in a retail store’s inventory.

#### Private Member Variables

| Variable Name | Description |
|--------------|-------------|
| itemNumber | An int that holds the item’s item number |
| quantity | An int for holding the quantity of items on hand |
| cost | A double for holding the wholesale per unit cost of the item |
| totalCost | A double for holding the total inventory cost of the item (quantity × cost) |

#### Public Member Functions

| Member Function | Description |
|----------------|-------------|
| Inventory() | Default constructor that sets all member variables to 0 |
| Inventory(int item, int qty, double c) | Constructor that accepts item number, quantity, and cost |
| setItemNumber(int item) | Stores the item number |
| setQuantity(int qty) | Stores the quantity |
| setCost(double c) | Stores the cost per item |
| setTotalCost() | Calculates and stores quantity × cost in totalCost |
| getItemNumber() | Returns the item number |
| getQuantity() | Returns the quantity |
| getCost() | Returns the cost per item |
| getTotalCost() | Returns the total cost |

#### Input Validation

The program should not accept negative values for:

- itemNumber
- quantity
- cost

If a negative value is entered, the user should be asked to enter the value again.

#### Example

```text
Enter item number: 101
Enter quantity: 5
Enter cost per item: 12.5

Inventory Details
Item Number: 101
Quantity: 5
Cost per Item: 12.5
Total Cost: 62.5
```

---

## Learning Objectives

After completing these experiments, students will be able to:

- Understand constructors and constructor overloading.
- Implement setter and getter functions.
- Apply encapsulation in C++ classes.
- Perform mathematical calculations using class methods.
- Design inventory management systems using classes.
- Validate user input in object-oriented programs.

## Technologies Used

- C++
- Classes and Objects
- Constructors
- Accessor and Mutator Functions
- Input Validation
- Object-Oriented Programming
