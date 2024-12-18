# Haskell Sort Function Type Error
This repository demonstrates an uncommon code error in Haskell related to the `sort` function from `Data.List`. The `sort` function works correctly with homogenous lists, but it throws a type error when presented with lists containing mixed data types (numbers and strings).  The solution involves using a type class to define a custom comparison function that handles different types gracefully. 

The `bug.hs` file contains the problematic code.  The `bugSolution.hs` file contains the corrected code and demonstrates how to resolve the type error.