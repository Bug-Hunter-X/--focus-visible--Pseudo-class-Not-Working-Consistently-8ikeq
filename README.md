# :focus-visible Pseudo-class Issue

This repository demonstrates a problem with the CSS `:focus-visible` pseudo-class.  The expected behavior is that the focus outline should only appear when the user interacts with an element using the keyboard or assistive technologies, not when using a mouse.  However, in this example, the outline appears regardless of input method.

The `bug.css` file contains the problematic CSS. The `bugSolution.css` file provides a possible solution.

## Reproducing the Bug

1. Clone this repository.
2. Open `index.html` (not included in this repo, but easily created) in your browser.
3. Observe that the focus outline appears when clicking on the button with the mouse, which is unexpected.
4. Test with different browsers and assistive technologies.  Inconsistent behavior may occur depending on browser implementation.

## Potential Causes and Solutions

The issue likely stems from browser inconsistencies in implementing `:focus-visible` or potential conflicts with other CSS rules.  The provided solution in `bugSolution.css` may offer a more robust solution in certain circumstances.  However, browser compatibility should always be tested thoroughly.
