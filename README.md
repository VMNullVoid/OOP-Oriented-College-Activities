# **This repository contains basically all of my studies from College about Object-Oriented-Programming, using JAVA.**
## ***"But what do these programs do? what problems do they solve?"***
## **Here's a quick resume about what each file on this repository do : ** 

### **Class Activity 1**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
##**Exercise 1**

### ***IN RESUME: Create the classes Faculdade (College), Aluno (Student), and Escola (School) with at least five attributes each.
***Instantiate objects for these entities and assign values. Add two methods to each class to simulate behaviors, such as a message indicating enrollment.***

● Create the structure of entity classes: Faculdade, Aluno, Escola
○ Each class must contain at least 5 atributes
● Create the objects & instances to each entity
○ Assign values to the created objects
● Change the classes in order to make them have at least 2 methods each
○ You can use a basic resource like: System.out.println("O aluno se matriculou") to simulate behavior and actions of the objects.

## **Exercise 2**
### ***IN RESUME: 
Create a class for a bus company and another to represent each individual bus, including attributes like mileage, passenger capacity, and driver name.
Add methods to check mileage (limit of 200 km), add/remove passengers (maximum of 60), and change the driver. Create a program to test these functionalities.***

### **a. Create the following classes:**
● A class that represents a bus company. Create atributes and methods to represent this class.
● A class to represent each individual bus of this company. Create atributes and methods to represent the class. Also, create a form to link the buses to the company
○ The Bus(Onibus) class must contain:
■ Bus atributes, mileage(quilometragem)->(double), quantity of passengers->(int) and the name of the driver->(String).
■ Use a builder method that allows the user to register a new bus.
■ A method that allows the verification of the bus mileage, in order that a bus that already reached 200Km of mileage gets prohibited to be driven.
■ A method that allows the addition of new passengers to the bus, respecting the passenger limit of 60 people.
■ A method that allows the removal of a person from the bus.
■ A method that allows the change of the bus driver of the individual bus.
###**b. Crie um programa que permita testar as Classes acima.**

## **Exercício 3**
### ***IN RESUME:
Create classes for a bank, account, and customer, including attributes and methods for banking operations (withdrawal, deposit, balance verification).
Allow the creation and linking of accounts to the bank and customers to the accounts.
Add a program to test these classes and implement transactions between customers.***

### **a. Create the following classes:**
● A class that represents a Bank instituition. Create atributes and methods to represent this class.
● A class that represents an account. Create atributes and methods to represent this class. Also, create a way to correlate the created accounts to the bank.
○ The account(conta) class must contain:
■ Atributes from the client's account, it's creation date and the balance.
■ A constructor method that allows the creation of a new account.

■ A method that allows the money withdraw.
■ A method that allows the deposit.
■ A method that allows the verification of the current balance.

● A class that represents the costumer. Create atributes and methods to represent this class. Also, create a way to correlate the costumer to the bank account.
○ The class must contain:
■ Costumer's atributes like name, social ID( CPF in Brazil) and adress.
■ A method or constructor that allows the creation of a new client.
■ A method that allows the print(on terminal)m método que permita imprimir os valores da conta do cliente.

### **b. Create a program that allows the testing of the below classes.**
### **c. Change the below program to permit transactions between different customers.**

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
### **Class Activity 2**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**Question 1:** 
*Implement through Java the inheritance that composes a superclass representing an Artist and subclasses of Singers, Keyboardists, Guitarists, and Drummers. 
Organize the classes to ensure inheritance among the classes, defining the main attributes and methods for each class.*

**Question 2:** 
*Implement through Java the inheritance that composes a superclass representing an Employee and subclasses of Engineers, Directors, Secretaries, Managers, Analysts, and Lawyers.
Organize the classes to ensure inheritance among the classes, defining the main attributes and methods for each class.*

**Question 3:** 
*Implement through Java the inheritance that composes a superclass representing an Animal and subclasses of 
Insects, Fish, Reptiles, Birds, Mammals, Wolves, Rabbits, Dogs, Cats, Crocodiles, Turtles, Eagles, Birds, Butterflies, and Ants.
Organize the classes to ensure inheritance among the classes, defining the main attributes and methods for each class.*

**Question 4:** 
*Implement through Java the inheritance that composes a superclass representing a Person and subclasses of 
Students, Teachers, Primary School Students, Higher Education Students, Primary School Teachers, Higher Education Teachers, Course Coordinators who also act as Teachers, and Directors.
Organize the classes to ensure inheritance among the classes, defining the main attributes and methods for each class.*

**Question 5:** 
*Implement through Java the inheritance that composes a superclass representing Equipment and subclasses of 
Household Appliances, Electromechanical Equipment, Hydraulic Equipment, Faucets, Electric Motors, TVs, DVDs, and Radios. 
Organize the classes to ensure inheritance among the classes, defining the main attributes and methods for each class.*
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|

### **Class Activity 3**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**Question 1:**
*Implement through Java the inheritance that composes a superclass representing an Animal and subclasses of Cat, Dog, Horse, Lion, and Ox.
Thus, using the concepts of polymorphism and method overriding, implement the method emitirSom() for each class, considering the following conditions:*

    The cat meows;
    The dog barks;
    The horse neighs;
    The lion roars;
    The ox moos.

**Question 2:**
Override methods entrarPontoDeEbulicao() and entrarPontoDeFusao() with specific boiling and freezing points.
*Implement through Java the inheritance that composes a superclass representing a Pure Substance and subclasses of Water, Ammonia, and Alcohol.
Thus, using the concepts of polymorphism and method overriding, implement the methods entrarPontoDeEbulicao() and entrarPontoDeFusao(), so that both methods receive decimal values considering the following conditions:*

    Water (Boiling point: 100 °C - Freezing point: 0 °C)
    Ammonia (Boiling point: -33.34 °C - Freezing point: -77.73 °C)
    Alcohol (Boiling point: 78.4 °C - Freezing point: 0 °C)

**Question 3:**
*Implement through Java the inheritance that composes a superclass representing a Calculator and subclasses of Multiplication, Division, Subtraction, and Addition.
Thus, using the concepts of polymorphism and method overriding and overloading, implement the method calcular() for each class so that it receives integer and decimal values.*

**Question 4:**
*Implement through Java the inheritance that composes a superclass representing a Computer and subclasses of Desktop, Notebooks, and Ultrabooks.
Thus, using the concepts of polymorphism and method overriding and overloading, implement the method informaCaracterísticas() for each class, 
ensuring there is one method that defines only the screen size, one method that defines the color, and one method that defines both the screen size and the color.*

**question 5:**
*Implement through Java inheritance that composes a superclass representing a Vehicle and subclasses of Car, Motorcycle, and Airplane.
Thus, using the concepts of polymorphism and method overriding and overloading, implement the methods aumentarVelocidade() and diminuirVelocidade() for each class, considering the following conditions:*

    The car increases speed by receiving a new speed value and a new gear to be modified.
    In this case, it will only increase speed if the speed and gear received as parameters are greater than the current ones. Furthermore, the speed cannot exceed 200 km/h, and the gear cannot exceed 5.
    The car decreases speed by receiving a new speed value and a new gear to be modified.
    In this case, it will only decrease speed if the speed and gear received as parameters are less than the current ones. Furthermore, the speed cannot be less than 0 km/h, and the gear cannot be less than 1.
    The motorcycle increases speed by receiving a new speed value and a new gear to be modified.
    In this case, it will only increase speed if the speed and gear received as parameters are greater than the current ones. Furthermore, the speed cannot exceed 100 km/h, and the gear cannot exceed 4.
    The motorcycle decreases speed by receiving a new speed value and a new gear to be modified.
    In this case, it will only decrease speed if the speed and gear received as parameters are less than the current ones. Furthermore, the speed cannot be less than 0 km/h, and the gear cannot be less than 1.
    The airplane increases speed by receiving a new speed value, new altitude, and new air resistance to be modified.
    In this case, it will only increase speed if the speed and altitude received as parameters are greater than the current ones and the current resistance is less than the current one. Furthermore, the speed cannot exceed 1000 km/h, the altitude cannot exceed 3000 meters, and the air resistance must be less than 50.
    The airplane decreases speed by receiving a new speed value, new altitude, and new air resistance to be modified.
    In this case, it will only decrease speed if the speed and altitude received as parameters are less than the current ones and the current resistance is greater than the current one.
    Furthermore, the speed cannot be less than 100 km/h, the altitude cannot be less than 1000 meters, and the air resistance must be greater than 100.
    
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|

### **Semester's last activity**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**Activity 1**
**IN RESUME: Create a college management system with a menu for managing students, subjects, and courses. Each menu option includes submenus for registering, consulting, removing, and updating entities.
Students must be linked to courses, courses to subjects, and data should include details like names, ages, and academic information.
Use lists to store objects, and ensure proper relationships between entities.**

***Create a system to manage college students and their courses and subjects! You should implement your system according to the information below:***
**01 - Create a system with a MENU with the following options:**
      
      1 - Manage STUDENTS
      2 - Manage SUBJECTS
      3 - Manage COURSES
      4 - EXIT
**02 - Create a SUBMENU with the following options for option 1:**

      1 - Register STUDENT
      2 - Consult STUDENT
      3 - Remove STUDENT
      4 - Update STUDENT
      5 - Return to MAIN MENU
**03 - Create a SUBMENU with the following options for option 2:**

      1 - Register SUBJECT
      2 - Consult SUBJECT
      3 - Remove SUBJECT
      4 - Update SUBJECT
      5 - Return to MAIN MENU
**04 - Create a SUBMENU with the following options for option 3:**

      1 - Register COURSE
      2 - Consult COURSE
      3 - Remove COURSE
      4 - Update COURSE
      5 - Return to MAIN MENU
**05 - Develop each of the functionalities of the SUBMENUS.**
**06 - A STUDENT must have a COURSE (and additional data such as name, age, etc.).**
**07 - A COURSE must have SUBJECTS (and data such as course name, shift, etc.).**
**08 - A SUBJECT must have a name, workload, grade, etc.**
**09 - Remember to only exit the program by choosing the EXIT option.**

        Note: Use LISTS to save the objects.
        Note: When displaying student data, the system must show their course and all subjects.
        Note: When registering a student, one of the existing courses must be chosen.
        Note: When registering a subject, it must belong to a specific course.
        
**Activity 2**
**IN RESUME:Develop a client and bank account management system.
The menu should manage clients and accounts, with submenus for registering, consulting, removing, and updating clients,
as well as creating accounts, withdrawing, depositing, checking balances, and transferring money between accounts.**

***Create a system to manage clients and their bank accounts! You should implement your system according to the information below:***
**01 - Create a system with a MENU with the following options:**

      1 - Manage CLIENTS
      2 - Manage ACCOUNTS
      3 - EXIT
**02 - Create a SUBMENU with the following options for option 1:**

      1 - Register CLIENT
      2 - Consult CLIENT
      3 - Remove CLIENT
      4 - Update CLIENT
      5 - Return to MAIN MENU
**03 - Create a SUBMENU with the following options for option 2:**

      1 - Create ACCOUNT for a CLIENT
      2 - Withdraw money from a CLIENT's ACCOUNT
      3 - Deposit money into a CLIENT's ACCOUNT
      4 - Check the balance of a CLIENT's ACCOUNT
      5 - Transfer money from one CLIENT's ACCOUNT to another CLIENT
      6 - Return to MAIN MENU        
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
