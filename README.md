# Tip Calculator

## Description
The Tip Calculator project is a web application that enables users to calculate the total bill per person when splitting the bill with a group. This application is built using HTML, CSS, and JavaScript. It provides a user-friendly interface and offers the following functionalities:

![Screenshot (151)](https://github.com/rjrahul08/Tip-Calculator/assets/61372250/cf9206be-dd10-49e3-99c7-0fb42f19d179)


### Functions:
1. `calculateBill()`: This function calculates the total bill per person based on the bill amount and tip percentage provided by the user. It updates the result on the DOM, displaying the amount owed per person.
2. `increasePeople()`: Use this function to increase the number of people the bill is split between. It updates the DOM with the new number of people and recalculates the bill accordingly.
3. `decreasePeople()`: Use this function to decrease the number of people the bill is split between. It prevents the number of people from going below 1 and alerts the user if they attempt to do so. The function updates the DOM with the new number of people and recalculates the bill accordingly.

## How to Use
1. Clone this repository to your local machine or download the ZIP file.
2. Open the index.html file in your web browser.
3. Enter the bill total in the "Bill Total" input field.
4. Enter the tip percentage in the "Tip" input field.
5. The number of people is initially set to 1; you can increase or decrease the number of people using the corresponding buttons.
6. The "Total Per Person" field will display the calculated amount owed by each person after splitting the bill.

## Important Notes
- The project uses the following DIV IDs to access various elements on the page:
  - `billTotalInput`: User input for the total bill amount.
  - `tipInput`: User input for the tip percentage.
  - `numberOfPeople`: Displays the current number of people the bill is split between.
  - `perPersonTotal`: Displays the total dollar value owed per person after the calculation.
- The functions (`calculateBill()`, `increasePeople()`, and `decreasePeople()`) are hard-coded in the HTML and cannot be changed.
- The project retrieves the number of people from the `numberOfPeople` div and stores it in a variable for reference during calculations.

Feel free to use this Tip Calculator app to easily split bills with your friends and enjoy accurate and hassle-free financial calculations!
