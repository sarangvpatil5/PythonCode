Guess the number code explanation

-first, the code will start by importing the required libraries. 
If libraries aren't installed then install it from a terminal by giving   --- pip install "library name" -----
here required libraries are: Random and time library
random library generates a random integer between 1 and 100 using the   ---random.randint---   method.

-then, it will run in a loop for a given Second (time) using the range method. After each iteration, it prompts the user to input a natural number between 1 and 100.

-If the user enters something that's not a natural number, the program will Display an error message and continue to the next iteration.

-If the user enters a valid natural number, the program converts the input into an integer using ----int(Number_Guess)---. The program will check if the input is equal to the randomly generated number. 
If it is, the program prints a ---Hola! You guessed the number in x attempts --- message and breaks out of the loop.

-If the input is |not equal| to the randomly generated number, the program prints a message to the user indicating whether their guess was ---Too high! Try a Smaller number OR too low! Try a larger number---.

-After each guess, the program pauses for one second using the ----time.sleep---- method.

-If the user is not able to guess the correct number within the allotted time (Y seconds here it's 4), the program prints a message indicating that time is up and reveals the randomly generated number.

