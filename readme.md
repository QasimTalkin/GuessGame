# Guess a Number Game

A script (embedded in an HTML5 document) that plays a “guess the number”
game as follows:
rogram chooses the number to be guessed by selecting a
random integer in the range from 1 to 1000. The script displays the prompt “Guess a
number between 1 and 1000” next to a text field. The player types a first guess into
the text field and clicks a button to submit the guess to the script. If the player’s guess
is incorrect, your program should display “Too high. Try again.” or “Too low. Try
again.” to help the player zero in on the correct answer. When the user enters the
correct answer, display “Congratulations. You guessed the number!”.

If the number is fewer than 10, display “Either you know the secret or you got
lucky!”. 

If the player guesses the number in 10 tries, display “Ahah! You know the
secret!”. 

If the player makes more than 10 guesses, display “You should be able to do
better!” In addition, handle incorrect input: 

If the player’s input is not a number,
display “Wrong input! You should enter a number between 1 and 1000.” and do not
count that guess.
