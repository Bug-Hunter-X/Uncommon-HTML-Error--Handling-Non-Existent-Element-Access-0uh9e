# Uncommon HTML Error: Handling Non-Existent Element Access

This repository demonstrates a subtle yet common error when working with HTML and JavaScript: attempting to access an element by ID that doesn't exist in the document.  Directly accessing a non-existent element results in a runtime error, halting the script's execution.

The `bug.html` file shows the problematic code where the script tries to add content to an element that might not be present. The `bugSolution.html` file demonstrates the correct approach using a conditional check to ensure the element exists before attempting to modify it, adding robust error handling that catches and reports the non-existent element.

This is a crucial concept to understand for writing reliable and robust JavaScript code that interacts with HTML elements.