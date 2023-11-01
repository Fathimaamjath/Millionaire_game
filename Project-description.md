# Millionaire_game
A user friendly game developed in jupyter notebook with multiple choice option so that the contestant can win a cash prize with an assistance of three lifelines. For implementing this game in jupyter notebook we are using tkinter module.

Tkinter Module

Tkinter (Tk-interface) is the standard GUI library for Python. 
Python when combined with Tkinter provides a fast and easy way to create GUI applications.
Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit.
Tkinter provides various controls, such as buttons, labels and text boxes used in a GUI application. 
These controls are commonly called widgets.

IMPLEMENTATION

Creating a GUI application using Tkinter is an easy task. Steps include:


Step 1: Import the Tkinter module.


Step 2: Create the GUI application main window.

Entire window is divided into two frames - Right and left frame.

  Left frame is again divided into 3 frame – Top, Center, Bottom

    Top frame  includes lifeline buttons for helping the contestants

    Center frame includes the logo of  “who wants to be a millionaire ”

    Bottom frame includes the layout for holding the questions and multiple choice options.

 Right frame 
    
    Includes the pictures of amount scored by the contestant

Insert question area and four option buttons.
Create a list for questions with 15 questions.
Create a list for option A, option B, option C, option D that includes multiple answers.
Create a list that includes all the correct answers
Load every image of amount scored by the contestants and make a list of that.
Place labels A,B,C,D inside the option button

Step 3: Add one or more of the above-mentioned widgets to the GUI application that performs the following functions.

[1] Create a function to call questions from the question list and related options.
Check for the correct answer and if it is correct call the next question from the list and change the options.
When the question is correct we need to change the amount image also.

[2] Include function when the contestants give wrong answer.
We need a new window with a message ‘you lose’ along with two sad smiley faces
This window also contains two buttons , to close the game and for try again.

[3] Include function when the contestants give all correct answer.
We need a new window with a message ‘you won’ along with two sad smiley faces.
This window also contains two buttons , to close the game and for play again.


[4]We need to add functions for all the helpline buttons.
We need to disable each button and change the image once it is used.

For 50-50 lifeline we need to remove two options  excluding the correct ones.

For audience pole we need to show a bar chart that shows the percentage of each answer to be correct and the right one should show higher value. 

For phone a friend we need to import a new library pyttsx3.
Pyttsx3 is a text-speech conversion library used in python. 
The pyttsx3 module supports two voices male and female. 
When we select this button we need an extra image of a phone along with a ringing sound.
So that its looks like calling and when we click on that we can hear the answers.
Once the button is used we have to disable that button and change the image.


Step 4: Enter the main event loop to take action against each event triggered by the user.




