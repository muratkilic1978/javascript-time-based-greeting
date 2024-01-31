# JavaScript Exercise: Greeting Based on Time of Day

## Step 1: Setting Up the Date
1.1. Declare a variable named `today` and set it to a new `Date` object:
   ```javascript
   let today = new Date();
   ```
   
## Step 2: Get the Current Hour   
Declare a variable named hourNow and get the current hour from the today object:

## Step 3: Define Greeting Variable
Declare a variable named greeting:

## Step 4: if conditions 
Check if the current hour is greater than or equal to 18 (6 PM) and assign the greeting 'Good evening!' if the condition is true.

## Step 5: else if conditions 
If the first condition is false, check if the current hour is greater than or equal to 12 (noon) and assign the greeting 'Good afternoon!' if the condition is true.

## Step 6: else if conditions 
If the second condition is false, check if the current hour is greater than or equal to 5 (5 AM) and assign the greeting 'Good morning!' if the condition is true:

## Step 7: else if conditions
If the third condition is false, check if the current hour is greater than or equal to 0 (midnight) and assign the greeting 'Late night!' if the condition is true:

## Step 8: else (Deafult Greeting)
If none of the conditions are met, set a default greeting 'Welcome!' to greeting:

## Step 9: Display Greeting message on Website
Update the HTML by writing some javascript code that can grab the "greetingMessage" ID through javascript. Hint you should use  'getElementByID' to fecth and ID on HTML and textContent to update and display the greeting message.