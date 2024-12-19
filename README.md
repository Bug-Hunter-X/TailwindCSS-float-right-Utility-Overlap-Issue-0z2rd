# TailwindCSS float-right Overlap Issue

This repository demonstrates an uncommon bug encountered when using the `float-right` utility class in Tailwind CSS. The button, intended to float to the right, unexpectedly overlaps or interacts undesirably with other elements.

## Bug Description

The `float-right` utility class in Tailwind CSS, when applied to a button within a parent container, does not always correctly float the button to the right. It may overlap with other content or exhibit unpredictable behavior based on parent element styling and context.

## Solution

The solution involves using flexbox or grid for reliable layout instead of relying solely on floats.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected overlapping of the button.
4. Open `bugSolution.html` to see the corrected implementation.