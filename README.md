# Lesson 8 Practice Hands On
Lesson 8 Practice Hands-On
Directions
For your Lesson 8 Practice Hands-On, you will be practicing your new jQuery skills. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page. Note that the solution will be slightly different from yours, but should look similar.

Setup
Open up your terminal/command prompt.

Navigate to your desktop in your terminal.

cd Desktop
Next, navigate to the FullStackWeb directory in your terminal.

cd FullStackWeb
Then, navigate to the FrontEndFoundations directory in your terminal.

cd FrontEndFoundations
Create a new project folder named L08HandsOn located within the FrontEndFoundations folder in your terminal.

mkdir L08HandsOn
Once the process is complete, navigate into the L08HandsOn directory:

cd L08HandsOn
Run the following to open your new project in VS Code (or you can open the folder within VS Code directly):

code .
Create three new files: index.html, style.css, and script.js in VSCode by selecting the add file button shown below:

newFile

Requirements
Add the following to the respective files. Don't forget to link your style.css, script.js, and add the jQuery CDN to your HTML page!

Step 1
index.html file:

A header that includes a page title and background color
A paragraph that says "Click here to learn more about jQuery!"
An unordered list of the following programming languages:
JavaScript, C#, Java, Ruby, Python
Two inputs: one for first name and last name
Make sure to label the inputs
Step 2
script.js file:

When the header is hovered over with the mouse, the font color should change and when the mouse stops hovering, it returns to the original color.
When the paragraph element is clicked on, it should populate the following paragraph: "jQuery is a fast, JavaScript library that makes many tasks easier and simpler to accomplish. A JavaScript library contains pre-written JavaScript which makes developing applications a bit easier for the developer. This means jQuery is not a language, but an extension of JavaScript. It takes many lines of JavaScript code, which we would have had to write ourselves before jQuery, and compresses it."
Hint! You will be using a new jQuery method: .text()

When a list element is double clicked on, it should be hidden from view
When typing in an input, on keydown, toggle the following class:
.input{
    color: red;
}
Step 3
style.css file:

Style your page so it has a bit of life!
Example
Original Screen:hands on example

jQuery Change Screen:hands on example with change