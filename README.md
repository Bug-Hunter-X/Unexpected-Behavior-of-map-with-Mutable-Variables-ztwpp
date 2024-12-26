This repository demonstrates a subtle but common error in Swift when using the `map` function with mutable variables. The provided code snippet uses `map` to double the values in an array, but it may not behave as expected if you are expecting the original array to be modified.

The `bug.swift` file contains the erroneous code, while `bugSolution.swift` demonstrates a corrected approach using `map` to create a new array while leaving the original array intact.

This example highlights the importance of understanding Swift's immutability principles and the correct usage of the `map` function. The solution emphasizes the creation of a new array instead of mutating the original one, thus adhering to functional programming principles and preventing potential side effects.