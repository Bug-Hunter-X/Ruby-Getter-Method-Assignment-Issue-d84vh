# Ruby Getter Method Assignment Bug

This repository demonstrates a common error in Ruby: attempting to modify an object's state through its getter method.  The code in `bug.rb` shows how assigning a value to the result of a getter method does not change the object's internal state.  The corrected version in `bugSolution.rb` uses a setter method for proper modification.

This is a frequent mistake for developers who are accustomed to languages with implicit getter/setter mechanisms.  Understanding the explicit nature of Ruby's methods prevents this type of error.