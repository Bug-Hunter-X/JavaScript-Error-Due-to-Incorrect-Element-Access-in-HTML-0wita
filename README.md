# Uncommon HTML Bug: Incorrect Element Access

This repository demonstrates a subtle bug in HTML where a JavaScript error arises from attempting to access a non-existent element using `document.getElementById()`. The HTML structure itself appears correct, making this bug harder to identify.

## Bug Description:
The `bug.html` file contains a `div` with the ID `myDiv`. However, the JavaScript code tries to modify the `innerHTML` of a `div` with the ID `myDiv2`, which does not exist. This results in a `TypeError` in most browsers.

## Solution:
The `bugSolution.html` demonstrates the solution; ensuring the element exists before attempting to modify it using an appropriate check.