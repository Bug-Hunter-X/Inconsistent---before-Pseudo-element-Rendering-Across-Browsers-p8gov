# Inconsistent ::before Pseudo-element Rendering

This repository demonstrates an uncommon CSS bug related to inconsistent rendering of the `::before` pseudo-element across different browsers. The issue arises from the use of a CSS selector that, while valid in many modern browsers, might not be supported by older or less common browsers.

## Problem

The `bug.css` file contains CSS code that uses the `::before` pseudo-element to insert content before an element.  While this works fine in most modern browsers, older browsers or those with less complete CSS support may fail to render the content correctly. This causes inconsistencies in the visual appearance of the web page depending on the user's browser.

## Solution

The `bugSolution.css` file provides a solution that uses a more widely supported approach to achieve the same visual effect, ensuring consistent rendering across different browsers. It uses a fallback mechanism for older browsers.