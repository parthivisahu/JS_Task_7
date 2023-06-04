# JS_Task_7
# JavaScript Program to Calculate Multiplication and Division of Two Numbers

This JavaScript program allows the user to input two numbers and calculates their multiplication and division. The program prompts the user for input and displays the results.

## Usage

1. Include the JavaScript program in your code or script file:

   ```javascript
   // Prompt the user for input
   const number1 = parseFloat(prompt('Enter the first number:'));
   const number2 = parseFloat(prompt('Enter the second number:'));

   // Perform multiplication and division
   const multiplication = number1 * number2;
   const division = number1 / number2;

   // Display the results
   console.log(`Multiplication: ${multiplication}`);
   console.log(`Division: ${division}`);
   ```

2. Run the program or trigger it through an event in your HTML file:

   ```html
   <script src="calculator.js"></script>
   ```

   When the program runs, it prompts the user to enter two numbers. It then calculates their multiplication and division and logs the results to the console.

   Alternatively, you can customize the program to display the results in a different way, such as updating HTML elements or showing an alert.

## Example

```javascript
// Prompt the user for input
const number1 = parseFloat(prompt('Enter the first number:'));
const number2 = parseFloat(prompt('Enter the second number:'));

// Perform multiplication and division
const multiplication = number1 * number2;
const division = number1 / number2;

// Display the results
console.log(`Multiplication: ${multiplication}`);
console.log(`Division: ${division}`);
```

When the program runs, it prompts the user to enter two numbers. For example, if the user enters 5 and 2, the program calculates the multiplication as 10 and the division as 2.5. The results are then logged to the console:

```
Multiplication: 10
Division: 2.5
```

Feel free to modify the program to suit your needs, such as adding error handling for invalid inputs or formatting the results differently.
