# Unintentional Global CSS Rule Hiding Elements

This repository demonstrates a common CSS bug where a globally applied rule unintentionally hides elements.  The bug is caused by using a class selector without sufficient specificity to target only the desired elements. 

## Bug Description

The `bug.css` file contains a CSS rule that hides all elements with the class `modal`.  This unintentionally hides modals where you might want them to be visible based on certain conditions.

## Solution

The `bugSolution.css` file demonstrates a solution that addresses this issue. It uses more specific selectors or modifies the existing rule in order to improve the control over how the modal class is applied.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (create this file if necessary) in your browser. 
3. Observe that the modal is always hidden.
4. Replace `bug.css` with `bugSolution.css` and observe the improved behavior. 