# CSS Float Issues with Undefined Height

This repository demonstrates an uncommon CSS bug related to floating elements and undefined heights.  The `bug.css` file contains the problematic CSS rule, and `bugSolution.css` provides the solution.

The issue arises because floating elements require a defined height, or a defined height on the parent container, for proper rendering in all browsers.  Without this, unexpected layout behavior may occur.