# Burger Simulation

This Java project simulates a burger ordering system with different types of burgers and toppings.

## Description

The project includes classes for a basic Hamburger, Healthy Burger, and Deluxe Burger. Each class represents a specific type of burger with its own ingredients and pricing. The project demonstrates object-oriented programming concepts such as inheritance, method overriding, and encapsulation in Java.

## Classes

### Hamburger Class

Represents a basic hamburger with customizable toppings. Includes methods for adding toppings and calculating the total price.

### HealthyBurger Class

Extends the Hamburger class and adds additional healthy toppings. Includes methods for adding healthy toppings and calculating the total price.

### DeluxeBurger Class

Represents a deluxe hamburger with fixed toppings. Inherits from the Hamburger class but overrides the topping addition methods to prevent customization.

## Usage

1. Create instances of different burger classes:
   ```java
   Hamburger hamburger = new Hamburger("Basic", "Sausage", 3.56, "white");
   HealthyBurger healthyBurger = new HealthyBurger("Bacon", 5.67);
   DeluxeBurger db = new DeluxeBurger();
# Burger Customization Instructions

Use the methods provided by each class to customize and order burgers:

1. **addHamburgerAddition1(String name, double price):**
    - Description: Add the first topping to the burger.

2. **addHamburgerAddition2(String name, double price):**
    - Description: Add the second topping to the burger.

3. **addHamburgerAddition3(String name, double price):**
    - Description: Add the third topping to the burger (only available for the Hamburger class).

4. **addHealthyAdditional1(String name, double price):**
    - Description: Add a healthy topping to the healthy burger (only available for the HealthyBurger class).

5. **itemizeHamburger():**
    - Description: Calculate and display the total price of the burger.
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
