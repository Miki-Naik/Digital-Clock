# Digital-Clock
Digital Clock implementation with Pause-Resume using JS classes

 Display a digital clock
 ***** Challenge ***** Using only html, css, and javascript create an html page that displays a clock in the format HH:MM:SS. It should work like an actual clock and display the current time (updating in real time) to the viewer. 
You must also provide the user with the ability to pause the clock and then resume the clock  ***** 

 ***** Documentation *****
    Note: The requirement that clock's functionality must exist in class is ambigious. 
    Is it a regular function / prototypal inheritance / classes in ES6 ? 

 ***** Assumptions and Implementation  ***** 
    1. To replicate how classes function in other languages, I used prototypal inheritance to implement my clock "class" 
    2. In JS, functions are objects. DigitalClock is my object that implements all of clock's functionality
    3. DigitalClock has 3 prototypal methods: displayTime, pause and resume.
    4. For pause and resume functions, I used bind() method to bind my current interval variable that needs to be set 
       and cleared respecitively.
    5. Implemented call() on window.onload when the clock functions reset its state. 
    6. Since it is a really small project, included styles and scripts within the html file. External files must be included
       for bigger projects. 
