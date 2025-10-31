#Number guessing game
This project is about a number guessing game algorithm
-Project Author: Ajeigbe Feranmi Joshua
-Pair reviewer: Stella Babayemi

NUMBER GUESSING GAME ALGORITHM:
#NUMBER GUESSING GAME
BEGIN
    Generate a random number between 1 and 10 and store it in SECRET_NUMBER

    DISPLAY "Welcome to the Number Guessing Game!"
    DISPLAY "I have chosen a number between 1 and 10. Can you guess it?"
    SECRET_NUMBER = 1,2,3,4,5,6,7,8,9,10
    REPEAT
        PROMPT user to "Enter your guess: "
        READ USER_GUESS

        IF USER_GUESS < SECRET_NUMBER THEN
            DISPLAY "Too low! Try again."
        ELSE IF USER_GUESS > SECRET_NUMBER THEN
            DISPLAY "Too high! Try again."
        ELSE
            DISPLAY "Congratulations! You guessed the correct number!"
        ENDIF

    UNTIL USER_GUESS = SECRET_NUMBER

    DISPLAY "Game Over. Thanks for playing!"
END