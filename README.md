# CSS Specificity Bug: Unexpected Style Overriding

This repository demonstrates a subtle bug related to CSS specificity.  The issue arises when combining ID selectors with class selectors. While intuitive, the unexpected behavior highlights the importance of understanding CSS specificity rules.

## Problem

The `bug.css` file contains CSS code that unexpectedly overrides a style when combining ID and class selectors. The expected behavior is for the combined selector to be applied, but due to specificity rules, a more general ID selector takes precedence. 

## Solution

The `bugSolution.css` file offers a solution to solve the unexpected behavior. By understanding and correctly managing CSS selector specificity, we can create consistent and predictable styling across different browsers.