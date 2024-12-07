# Proposal

## What will (likely) be the title of your project?

Qubit simulator.

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

 A program that calculates the probability that a qubit sent from one person to another will be recieved as a 1 or 0.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The program will use two 3x3 basis matrices input by the user as a simulation of the quibit being sent between them. If both bases are the same, whatever Alice sends Bob will be correctly recieved as a 1 or 0. As Bob rotates his basis according to a rotation matrix, the likelyhood of him recieiving the correct bit decreases until it reaches 0 at 90 degrees of rotation. The program will display the likelyhood of Bob recieving th ecorrect bit from Alice based on the bases input by the user. The inputs will simply be entered into two 3x3 boxes to keep the ui as simple as possible.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N/A

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

The user will be able to input the values of the two matrices and the probability will be properly displayed.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

The inputs won't be typed out in order like how matrices normally function in the math module, but will be entered into two 3x3 matrices that the user sees when the porgram is run.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

Program also supports inputs of complex numbers (common in real applications).

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I need to find a module that supports my idea for the ui that pops up upon running the program. I also need to figure out how to use for loops to do matrix multiplication.
