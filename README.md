# Ruby Dynamic Typing Issue

This repository demonstrates a potential issue related to Ruby's dynamic typing system.  The `bug.rb` file showcases how a method can accept different data types unexpectedly. This is an uncommon bug, usually missed unless very careful type checking is implemented. The `bugSolution.rb` provides a potential solution using type checking.

## Problem Description

The `MyClass` class allows assigning any data type to the `@value` instance variable.  While flexibility is a benefit of dynamic typing, it introduces the risk of unexpected behavior if the variable is used in a type-sensitive manner later in the code.