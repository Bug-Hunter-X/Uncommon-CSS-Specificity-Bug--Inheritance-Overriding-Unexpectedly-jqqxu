# Uncommon CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance.  The issue revolves around the unexpected behavior of inheritance when dealing with more specific selectors. The `bug.css` file contains the problematic code, while `bugSolution.css` offers a solution. 

## Problem

The primary problem is that a more specific selector (`div p`) doesn't always override inherited properties from a less specific ancestor selector (`div`).

## Solution

The solution involves understanding and correctly managing CSS specificity and inheritance. The `bugSolution.css` file provides a corrected version of the CSS to achieve the expected behavior.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` in a web browser. Observe the unexpected color of the text within the `<p>` tag.
3. Open `bugSolution.html`. Observe the corrected color and the expected behavior.