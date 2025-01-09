# CSS calc() function unexpected behavior
This repository demonstrates an uncommon error related to the CSS `calc()` function. The error arises from either missing units or inconsistent unit usage within the calculations.

## Bug Description
The `calc()` function in CSS provides dynamic calculations for CSS properties.  However, using it incorrectly—for example, omitting units in the calculation or mixing inconsistent units—can cause unexpected behavior and rendering issues.

## Reproduction Steps
1.  Open `bug.css` and observe the incorrect implementation of `calc()`. 
2.  Examine the resulting layout in a web browser. You'll notice that the layout does not behave as expected due to the missing unit in the calculation.
3.  View `bugSolution.css` to see the corrected calculation with units.

## Solution
Ensure that all values within the `calc()` function have consistent units. If you are subtracting or adding pixel values, ensure both terms are pixels.  Similarly, percentages should be used consistently with percentages.
