# CSS Specificity Issue: Unexpected Style Overriding

This repository demonstrates an uncommon bug in CSS related to selector specificity. The problem arises when trying to style a parent element and its child element with different background colors.  Due to CSS specificity rules, the style applied to the child element overrides the style of the parent element.

## Bug Description:
The CSS code attempts to style a container and its paragraph elements with different background colors. However, the style applied to the paragraph inside the container overrides the container's background color.

## How to Reproduce:
1. Open `bug.css`.
2. Observe that the paragraph inside the container has a lightgreen background, instead of inheriting lightblue from the container.

## Solution:
The solution involves understanding and utilizing CSS specificity correctly.  This involves carefully choosing your selectors and ensuring the appropriate specificity for your intended style application.

See `bugSolution.css` for a corrected implementation.