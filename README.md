# Tailwind CSS @apply Directive Pseudo-Selector Issue

This repository demonstrates a bug in Tailwind CSS's `@apply` directive where it doesn't correctly handle pseudo-selectors like `:hover`, `:focus`, and `:active` when applied directly within the `@apply` directive.  This leads to unexpected styling behavior.  The solution demonstrates an alternative approach that correctly applies these styles.

## Bug

The bug is showcased in `bug.css` file. The `@apply` directive fails to expand the hover state correctly, resulting in no hover effect on the button.

## Solution

The solution is provided in `bugSolution.css`. The hover effect is correctly applied by separating the pseudo-selector styles from the `@apply` directive.