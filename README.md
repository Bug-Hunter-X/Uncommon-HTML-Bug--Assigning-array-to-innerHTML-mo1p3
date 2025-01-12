# Uncommon HTML Bug: Assigning Array to innerHTML

This repository demonstrates a subtle bug in HTML related to the misuse of the `innerHTML` property.  Attempting to assign an array directly to `innerHTML` will not render the array's contents as expected. Instead of showing the array elements, it will display a string representation of the array.

The solution provided shows the correct way to render an array's contents using string manipulation or other alternative methods.

## Bug
The bug is located in `bug.html`.

## Solution
The corrected code is shown in `bugSolution.html`.