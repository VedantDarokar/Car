# Car_Rental_System

A simple command-line Java application that allows users to rent and return cars. It provides functionalities to manage car rentals, customers, and calculate rental prices.


* **Features**

1.Add and manage cars in the system.
2.Register customers for renting cars.
3.Rent and return cars with availability checks.
4.Calculate rental costs based on days rented.
5.Simple command-line interface for user interaction.




* **Installation**

1.Clone the repository :
```git clone https://github.com/VedantDarokar/Car_Rental_System.git```

2.Navigate to the project directory :
```cd Car_Rental_System```

3.Compile the Java files :
```javac src/*.java -d bin```

4.Run the application :
```java -cp bin Car_Rental_App```




* **Usage**
1.Start the application and choose from the menu options:
-Rent a Car
-Return a Car
-Exit
  

2.Follow the prompts to enter customer details and select available cars for rental.

3.Confirm your rental and view the rental information.

4.To return a car, enter the car ID, and the system will process the return.





* **Example Interaction**

```===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: John Doe

Available Cars:
C001 - Toyota Camry
C002 - Honda Elevet
C003 - Mahindra Thar

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==

Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 3
Total Price: 6000.00 INR
Confirm rental (Y/N): Y

Car rented successfully.
