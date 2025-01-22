# Tailwind CSS Gradient, Shadow, and Rounded Corner Issues

This repository demonstrates some uncommon issues that can arise when using Tailwind CSS gradients, shadows, and rounded corners.  The `bug.html` file showcases the problem, while `bugSolution.html` provides a possible solution.

## Problem

Using Tailwind's gradient feature, with colors drastically different in brightness or hue, can sometimes result in an unappealing or jarring gradient. Applying `rounded-lg` or `shadow-md` to complex elements might not yield expected results. 

## Solution

The solution focuses on carefully selecting gradient colors to ensure visual harmony.  Additionally, proper structuring of HTML elements and the use of appropriate Tailwind utilities helps to achieve the expected outcome for rounding and shadowing.  Consider using more specific utility classes for finer control over styles.