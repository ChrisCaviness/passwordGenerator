Christopher Caviness - Password Generator - ReadMe

1. Created a list of arrays for uppercase, lowercase, numbers, and special characters.

2. Created an array for for the end product (randomizedPassword) and an array for all the selected user selected arrays.

3. Created a while statment inside the generatePassword function to keep the user input between 8 and 128 characters. Followed by a prompt for the user to input a number.

4. Added a console.log to make sure the user input was noted.

5. Created a list of questions as window.confirm boxes asking if users wanted to use uppercase, lowercase, numbers, or special characters. With messages for each decision.

6. Added additional if statements if the users questions come back as true, adding different arrays to a master array to pull from called "selectedCharacters". Also using math to make sure that each array had at least one random value added to the end password, and logged to the console to prove it.

7. Used a for statement to take the overall selectedCharacters array and randomize it, producing a unique password.

8. Took the randomizedPassword variable, and used randomizedPassword.join('') to remove the commas seperating the characters.

9. Console logged the generated password, and the length of the password, with an additional window.alert to show the password.

10. Return randomizePassword to the screen.




Notes:
    I really could not figure out how to get the randomzied password to match the desired password length the user input. I could only get the entire arrays chosen to be added to the password in random order. Makes for a really great password, but without the required specifications. 

    I also couldn't figure out why when you run the generator multiple times, it merely adds the new password on to the end of the old password and continues going on and on. No idea what is happening there.
