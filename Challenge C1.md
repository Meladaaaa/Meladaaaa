SET START
SEND "Enter your heigth (in metres)." TO DISPLAY
RECEIVE heigth FROM KEYBOARD 
SEND "Enter your weight in kilograms)." TO DISPLAY
RECEIVE weight FROM KEYBOARD 
SET BMI TO weight/height^2
SEND "Your body mass index is" BMI TO DISPLAY
