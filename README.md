# Flexbox Item Width Calculation Issue

This repository demonstrates an uncommon issue related to width calculations in CSS flexbox layouts when the parent container has padding or borders.

The problem is that the width of a flex item specified as a percentage is calculated relative to the available space *within* the parent container, after accounting for padding and borders.

The `bug.css` file showcases the problem, while `bugSolution.css` illustrates several solutions to resolve the unexpected behavior.

This is a relatively subtle issue that can easily be overlooked but can lead to unexpected layouts.