# Uncommon HTML Bug: innerHTML on Non-Existent Element

This repository demonstrates a subtle but potentially impactful bug in HTML/JavaScript interaction.  The bug arises from attempting to modify the `innerHTML` property of a DOM element that does not yet exist. This commonly results in a JavaScript error, interrupting further script execution.

The `bug.html` file showcases the problematic code. The `bugSolution.html` file provides a corrected version, demonstrating best practices.

## Bug Description
The code attempts to manipulate the `innerHTML` of an element that is not present in the DOM when the script executes.  This leads to a runtime error.  While many common errors involve syntax or simple logic, this example highlights a dynamic error related to DOM manipulation.

## Solution
The solution focuses on ensuring the element exists before attempting to use `innerHTML`.  This can be achieved through various methods such as checking for the element's existence or using event listeners to ensure the DOM is ready.
