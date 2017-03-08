# jQuery_challenges-
Interactive Webpages with jQuery
These challenges should look familiar, but this time we would like you to improve them by using the pieces of jQuery functionality we covered. We have made some suggestions for how you could use jQuery within each of the challenges. You may have your own ideas for additional jQuery functionality, so don't feel limited to the suggestions we have made.

Note: It is really important to remember to use $(document).ready

Magic 8 Ball

As a user I can enter a question on a web page and magically get an answer to my question.

View

Create an input tag to accept questions from the user. Give it an id of "question".
Create a button tag to send the question to the Javascript code. Give it an id of "submit".
Create a p tag to hold the answer the Magic 8 Ball sends back. Give it an id of "answer".
Controller

Create a click listener for the button tag, which opens up an alert.
Make the click listener show what is in the input field. Use the jQuery function .val().
Make the click listener show what's in the input field in the paragraph section. Use the jQuery function .text().
Clear the input field after the button is clicked.
Reuse your code from the previous Magic 8 Ball challenge to give a random answer.
Hi/Lo Game

Remember the Hi/Lo Game? Let's create an interactive webpage that allows a user to play.

View

Create an input tag for the user's guess.
Create a button tag to send the user's guess to the Javascript code.
Create a p tag for the game's feedback (whether the guess is too high/too low/the user has won or lost).
Controller

Create a click listener that takes in the user's guess from the input tag and displays it in an alert.
Reuse the code from your previous Hi/Lo Game challenge to to match the user's guess to the correct set number.
Make the p tag red when there are only two guesses left. Use the jQuery .addClass(..) function.
Make the p tag contain the results of all the user's guesses. Use the jQuery functions .append(..) or .prepend(..) and .text(..).
Hide the button and input tags when the game is over, using the jQuery .show(..) and .hide(..) functions.
User ID and Password Validation

Recreate the basic credential validation challenge using jQuery.
The criteria are:

User ID and password cannot be the same
User ID and password have to be at least six characters long
User ID cannot contain the following characters: !#$
Password has to contain at least one of: !#$
Password cannot be "password"
Password has to contain at least one digit
Password has to contain a lower and an uppercase letter (hint: use toUpperCase or toLowerCase)
View

Create an input tag for the user ID.
Create an input tag for the password.
Create a button tag that sends the user ID and password to the Javascript code.
Create a p tag for the page's feedback to the user (whether the user's credentials are valid or invalid and any related error messages).
Controller

Create a click listener that takes the user ID and password from the input tags and displays them in an alert.
Reuse the code from your previous User ID and Password Validation challenge to compare the user's input to the criteria for a valid user id and password.
Show an error message in the p tag if the credentials are not valid and why. Use the jQuery functions .append(..) or .text(..).
Clear unacceptable values from the input fields after an attempted submission. Use the jQuery function .val(..).
Disable the button after a certain number of log in attempts have been made. Use the jQuery function .off(..).
Car Accelerator

View

Create a div for registering make, model, and year. Inside the div:
Create input tags for (model) year, make, and model.
Create a button tag to send the car information from the input tags to the Javascript code.
Create another div for showing the car information. Inside the div:
Create a p tag to display the car information in after the user clicks the button.
Create a p tag to display the car's speed.
Create a button tag to increase the car's speed.
Create a button tag to decrease the car's speed.
Controller

Create a click listener so that when the button in the first div is clicked, the first div disappears, the second div appears and shows the car information entered in the first div. Use the jQuery functions .show(..), .hide(..), and .text(..).
Reuse the code from your previous Car Accelerator challenge to make your cars objects with default speed, acceleration, and deceleration behavior.
Create a click listener that increases the speed when the user clicks on the accelerate button. Display the increases in the appropriate p tag.
Create a click listener that decreases the speed when the user clicks on the brake button. Display the decreases in speed in the appropriate p tag.
Make the car's speed red when the user is close to reaching the maximum speed. Use the jQuery function .addClass(..).
Hide the accelerate button once the maximum speed is reached.
Hide the brake button once the speed is 0.
