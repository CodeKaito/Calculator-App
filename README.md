# Calculator App

This is a simple calculator app built using JavaScript that can perform basic arithmetic calculations such as addition, subtraction, multiplication and division.

## Usage
- Launch the app by opening the `index.html` file in a web browser.
- Use the number buttons to input the values you want to calculate.
- Use the sign buttons to select the operation you want to perform.
- Click the equals button to get the result of your calculation.
- Click the clear button to reset the calculator.

## Code Overview

The calculator app is built using JavaScript and DOM manipulation. Here is a brief explanation of the code:

- The code starts by selecting the necessary HTML elements using `document.querySelectorAll()` and `document.querySelector()`.
- It then initializes some variables to keep track of the values being entered and the sign of the operation being performed.
- A `for` loop is used to add event listeners to the number buttons, so that when clicked, the corresponding value is added to the appropriate variable.
- There are separate functions to handle the first value, second value, and sign inputs.
- The `equals` button has an event listener that calculates the result based on the selected operation and displays it in the result field.
- There are two additional buttons - `percent` and `negative` - that modify the values and the result in specific ways.
- Finally, the `clear` button resets all the values and the result to their original states.

## Future Improvements

- The calculator could be improved to handle more complex operations, such as parentheses and exponents.
- The code could be refactored to make it more efficient and easier to read.
- Styling could be added to make the calculator more attractive and user-friendly.
