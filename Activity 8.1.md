SET START
SET mysNumb TO 3
SEND "Please enter guess number" TO DISPLAY
RECEIVE guess FROM KEYBOARD
IF guess > 10 THEN 
SEND "Too high! Your guess must be between 1 and 10" TO DISPLAY
ELSE IF GUESS = mystNumb? THEN
SEND " You guessed it corrected!" TO DISPLAY
ELSE
SEND "Badluck" TO DISPLAY
SET END
