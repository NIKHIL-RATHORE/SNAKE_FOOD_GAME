# SNAKE_FOOD_GAME
THIS IS GAME MADE BY USING BLESSED LIBRARY (Blessed is more than just a Python wrapper around curses: 
Styles, Colors, and maybe a little positioning without necessarily clearing the whole screen first.
Works great with Python’s new f-strings or any other kind of string formatting.
Provides up-to-the-moment Location and terminal height and width, so you can respond to terminal size changes.)

SNAKE CHASES THE FOOD AND HERE WE ARE THE FOOD RUNNING AWAY FROM SNAKE.
SNAKE GROWS LONGER IF IT DOESN'T EAT ANYTHING AND THE GAME STOPS IF SNAKE CATCHES FOOD OR BITES ITSELF
SPEED OF FOODS GREATER THAN SNAKE'S FOR OBVIOUS REASONS
THE WORLD VARIABLE IS A 2D ARRAY OR YOU CAN SAY A 2D LIST 
SNAKE IS PROGRAMATICALLY MADE BY DEQUE DATA STRUCTURE (which is helpful because when snake moves forward it can delete/add cells on either side)
POSITION OF SNAKE AND FOOD IS UPDATED EVERT FIXED AMOUNT OF TIME AND BY REDUCING THIS AMOUNT OF TIME WE CAN INCREASE THE SPEED OF SNAKE OR FOOD.
ALSO THE LOGIC FOR SNAKE FOLLOWING THE FOOD IS DONE BY COMPARING THE DIFFERENCE IN LOCATION OF HEAD OF SNAKE AND FOOD IN BOTH X AND Y DIRECTION AND DEPENDING
ON WHICH IS GREATER WE DECIDE BETWEEN MOVING IN HORIZONTAL AND VERTICAL DIRECTIONS AND THEN THE FINAL DECISION IS MADE BY IF X-DIFF//Y-DIFF IS +IVE OR -IVE

USE W,A,S,D OR ARROWS TO MOVE 

https://user-images.githubusercontent.com/99716198/183117463-db33c8d9-7717-425c-9f72-66fe453c942f.mp4

