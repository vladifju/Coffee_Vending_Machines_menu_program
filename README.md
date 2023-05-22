~Coffee Vending Machine

  This repository contains a Python program for a coffee vending machine. The program is designed using object-oriented programming principles and consists of several classes that model the machine, menu items, the menu itself, and the money handling mechanism.

~Classes

  CoffeeMaker:
This class represents the coffee making machine. It tracks the available resources such as water, milk, and coffee. The class provides methods for reporting the available resources, checking if there are sufficient resources to make a specific drink, and making a coffee by deducting the required ingredients.

  MenuItem:
The MenuItem class models each drink item available in the menu. It has properties like the name, cost, and required ingredients for the drink.

  Menu:
The Menu class represents the menu of the coffee vending machine. It contains a list of MenuItem objects and provides methods for retrieving all the available drink names and searching for a particular drink by name.

  MoneyMachine:
The MoneyMachine class handles the money-related operations of the vending machine. It keeps track of the profit, the money received from customers, and provides methods for reporting the current profit, processing coin payments, and making a payment.

~Usage
To use the coffee vending machine program, simply run the on_machine() function. This function starts the interactive session where you can select drinks from the menu, check the available resources, refill the machine, and turn off the machine.

During the interactive session, you can enter the name of the drink you want, "report" to get a report of available resources and profit, "refill" to refill the machine's resources, or "off" to turn off the machine.

The program will prompt for coins if required, calculate the payment, check the availability of resources, and dispense the selected drink if the payment is successful and resources are sufficient.


Note
This program is a simplified simulation of a coffee vending machine and does not include advanced features such as user authentication or real-time inventory management. It serves as a demonstration of basic functionality and object-oriented programming principles.

Feel free to explore and modify the code to enhance the functionality or add new features to meet your requirements.
