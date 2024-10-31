The program represents a simulation of a one-person lift sequence with 3 floors (0 - 1 - 2).
This means that one person can operate the lift at a time.
For example, if the person wants to go from floor 0 to 2, and another person wants to enter at floor 1, that this wont work

-= Visualisation =-
The visualisation consists of 4 parts
    - The outside user input with LED
    - The inside user input
    - Information strings i.e. the current floor of the lift and instructions on what to do next
    - LEDs to indicate the lift operations i.e. lift movement and opening / closing doors

-= Program =-
Note: Lift movement takes 3 seconds PER floor.

First, the lift is initialized at floor 0.

The user selects from which floor he want to call the lift. 

The lift will move accordingly by ether moving the lift or down, and opening the doors when the lift is at the target floor
These doors will stay open until the user the user presses the target floor from the inside.

Than the user has to press the target floor to which he / she wants to go.

The lift will move accordingly by ether moving the lift or down, and opening the doors when the lift is at the target floor
These doors will open for 3 seconds and the user can call for the lift again via the ouside button inputs