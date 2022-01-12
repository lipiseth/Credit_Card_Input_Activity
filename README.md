# Credit_Card_Input_Activity
Created an Android "screen" that would allow a user to enter and submit the following data from an American Express, Discover, MasterCard, or Visa credit card: 
--> Credit card number 
--> Expiration date (MM/YY format) 
--> CVV security code 
--> First name 
--> Last name

If any of the entered data was invalid, the user needed to be notified so they could correct it. In addition to not having issues like empty fields or badly-formed or expired expiration date, credit card data also had to meet these criteria to be considered valid:

Credit card numbers needed to be in a valid American Express, Discover, MasterCard, or Visa format 
Credit card numbers also needed to pass Luhn validation - see Luhn algorithm
The CVV had to meet these criteria: CVV criteria
First and last names could only contain characters that were "alphabetical and spaces"
When the user-submitted valid credit card data, the app should pop up an alert dialogue notifying them that the payment was successful.

