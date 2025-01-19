This repository demonstrates a common mistake when attempting to manipulate CSS styles using JavaScript in HTML. The bug showcases an incorrect way to set the display property of an element to make it visible.  The solution provides the correct implementation.

## Bug
The bug lies in the JavaScript code that attempts to make the div with the id "myDiv" visible.  The code incorrectly uses `document.getElementById("myDiv").display = "block";` instead of correctly using `document.getElementById("myDiv").style.display = "block";`

## Solution
The solution demonstrates the correct way to use the `style.display` property to control the visibility of the HTML element.