## Goals ##
the goal of this project is to get some basic understanding of how to implement an app in CSS grid. 

I will be implementing this with react



Components are as such:
    container for the app
    container for the display
    container for the buttons


A. a display (array) to keep track of a current value
B. memory for the previous value (number)
C. memory for an operation value
D. 16 buttons with function to:
    Clear, 1 button:
        clear current and previous value
    perform operations, 4 buttons: ADD, SUBTRACT, MULTIPLY, DIVIDE
        set previous value to be a number from the current array then store the operation valu9e
    punch in a number, 10 buttons:
        append number (0-9) to end of display list (current)
    equals button, 1 button:
        convert current array to a number
        perform the operation in "operation value" passing in previous value and the new number
        display operation result

