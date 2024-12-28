# Ruby Bug: Unexpected Behavior from Directly Modifying Instance Variables

This repository demonstrates a common, yet subtle, bug in Ruby related to directly modifying instance variables using `instance_variable_set`.  While functional, this approach bypasses any potential validation or access control within a class's methods and can result in unexpected and difficult-to-debug issues.

The `bug.rb` file showcases the problem. The `bugSolution.rb` illustrates how to improve code maintainability and readability by using accessor methods.