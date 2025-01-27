# CSS Specificity Bug: Last Declaration Wins

This repository demonstrates a common issue in CSS where the last declaration of a property overrides previous declarations.  The bug is shown in `bug.css`. The solution is provided in `bugSolution.css`, using more specific selectors or avoiding redundant declarations.

## Bug
The bug lies in the conflicting styles applied to a div.  Both `width: 50%;` and `width: 100%;` are applied, resulting in the element always having a width of `100%;`.

## Solution
The solution either utilizes more specific selectors to target the divs differently or removes the redundant styles.