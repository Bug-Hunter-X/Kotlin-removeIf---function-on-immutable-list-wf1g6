# Kotlin removeIf() on Immutable List
This example demonstrates the common error of using the `removeIf()` function on an immutable list in Kotlin.  The `removeIf()` function is designed for mutable lists, and attempting to use it on an immutable list will result in a compilation error.  The solution involves using a mutable list or creating a new list containing only the desired elements.

## Bug
The `bug.kt` file shows the error of trying to use `removeIf` on `listOf`. 

## Solution
The `bugSolution.kt` file demonstrates the correct usage of `removeIf` with a mutable list, providing a proper solution.