# F# Mutable Variable Swap Bug

This repository contains a bug report and solution for a common error in F# involving mutable variables and swapping their values.

## Bug Description

The original code attempts to swap the values of two mutable variables using a `swap` function. However, due to the order of assignments, the values are not swapped correctly.

## Solution

The solution demonstrates the correct way to swap the values of mutable variables in F#, using a temporary variable to store the initial value of one variable before reassigning.