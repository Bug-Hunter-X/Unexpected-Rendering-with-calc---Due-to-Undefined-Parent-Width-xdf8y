# Unexpected Rendering with calc() Due to Undefined Parent Width

This repository demonstrates a common error when using the `calc()` function in CSS. The issue arises when performing calculations that rely on the width of a parent container that doesn't have an explicitly defined width.

## Bug Description
The `bug.css` file contains CSS that attempts to calculate the width of an element based on its parent's width. However, the parent's width is not specified, leading to incorrect rendering.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS, ensuring that either the parent container has a defined width or the width calculation is adjusted to work without relying on an undefined parent width.