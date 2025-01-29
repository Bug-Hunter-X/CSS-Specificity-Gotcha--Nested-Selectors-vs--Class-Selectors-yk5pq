# CSS Specificity Issue: Unexpected Style Overrides

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected behavior when combining nested selectors and class selectors.  The problem arises when the specificity of selectors is not fully understood and leads to unintended style overrides.

## Problem Description

The provided CSS code shows a case where the style applied to a paragraph element within a div element does not behave as expected. A nested selector is expected to be more specific and therefore override a more general rule. However, a class selector can take precedence depending on the context and specificity levels.

## Solution

The solution demonstrates how to use a more specific selector (in this case using the class) or adjusting the order of CSS declarations to fix the unexpected style overrides.

## How to reproduce the issue:

1. Open `bug.css` and review the original CSS code that demonstrates the problem.
2. Create a simple HTML document and add elements according to the original CSS selectors to check the outcome. You'll observe that the green color does not apply as expected.
3. Open `bugSolution.css`. Review the updated code and observe how the unexpected behavior is solved.   Try applying the code to your HTML document to verify the corrected behavior.  
