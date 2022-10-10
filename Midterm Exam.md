 SEND Temperature TO DISPLAY
 RECEIVE Temperature FROM KEYBOARD 
 IF Temperature < 18 THEN 
    Send "Cold, the perfect temperature for sleep is 18 and 21 degrees."
 ELSE
    IF Temperature > 21 THEN
       Send "Perfect"
    ELSE 
       SEND "No!, the perfect temperature for sleep is 18 and 21 degrees."
    END IF
 END IF    
