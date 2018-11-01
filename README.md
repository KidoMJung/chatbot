# Chatbot Assignment
The assignment is to create the js logic based on Artificial Intellegence Markedup Language in the custom.js file

# Getting started
First download a text editor. I personally use VS Code.

# Actionplan: A) HTML (index.html)
-  We have to structure our code first and build the fundamentals on which our chatbot is built. We do this in our index.html file. The css is already given.
- The structure should contain a parent container of a chat screen with 3 children containers in it.
1. a container for the user messages we want to display. This should have an id of output and a class of messages and user-messages
2. a container for the chatbot's text. This should have an id of robotMessages and a class of messages and robot-messages.
- + the avatar.svg
3. a container for user input messages, where we type in our text. This should have a form element with in it a children container of input with id input. The input element should also have attributes of value, type and placeholder.
- + the fill-1.svg


# Actionplan: B) Javascript (custom.js)
1. Make a function named start that takes in 2 arguments. 
- 1nd argument should be the input of the user's text
- 2nd argument should be the output of the chatbot's text
-  Use 3 if statements inside the body of start function to make same text that checks the 2 arguments that are being passed in.
3. Use of DOM Manipulation in the out function, see comments in custom.js

#Extra challenge
- Make the textbox of the chatbot float to the bottom of the screen each time you ask it something the img should be displayed next to the textbox. You can do this with css or js.


