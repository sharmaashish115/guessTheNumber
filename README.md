# guessTheNumber
It's a simple program to guess a number in between 1 to 20 numbers.
First, the program imports the random module so that it can use the random.randint() function to generate a number for the user to guess. The return value, a random integer between 1 and 20, is stored in the variable secretNumber.
The program tells the player that it has come up with a secret number and will give the player six chances to guess it. Since input() returns a string, its return value is passed straight into int(), which translates the string into an integer value. This gets stored in a variable named guess.
Then it compares the input value from player with the secretNumber. And shows the results accordingly.
