# CSS calc() Miscalculation Bug

This repository demonstrates a common error when using the `calc()` function in CSS to calculate element widths. The issue arises when the calculation does not take into account the element's padding and border, leading to unexpected layout behavior.

The `bug.css` file shows the incorrect implementation, while `bugSolution.css` provides the corrected version.

## Bug Description

The CSS code attempts to set the width of an element to 100% minus 20px.  However, the padding and border of the element are not considered in the calculation, causing the element to render with a width slightly larger than intended, potentially overflowing its container.