# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This example demonstrates a common issue in Ruby where directly manipulating instance variables using `instance_variable_set` can lead to unforeseen problems and hinder maintainability.  Best practice is to always use accessor methods to interact with instance variables.