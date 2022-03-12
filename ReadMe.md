Christopher Caviness - Password Generator - ReadMe

1. Created a list of arrays for uppercase, lowercase, numbers, and special characters.

2. Created an array for for the end product (randomizedPassword) and an array for all the selected user selected arrays.

3. Created a while statment inside the generatePassword function to keep the user input between 8 and 128 characters. Followed by a prompt for the user to input a number.

4. Added a console.log to make sure the user input was noted.

5. Created a list of questions as window.confirm boxes asking if users wanted to use uppercase, lowercase, numbers, or special characters. With messages for each decision.

6. Added additional if statements if the users questions come back as true, adding different arrays to a master array to pull from called "selectedCharacters". Also using math to make sure that each array had at least one random value added to the end password, and logged to the console to prove it.

7. Used a for statement to take the overall selectedCharacters array and randomize it, producing a unique password.

8. Took the passwordResult variable, and used passwordResult.join('') to remove the commas seperating the characters.

9. Console logged the generated password, and the length of the password, with an additional window.alert to show the password.

10. Return passwordResult to the screen.

