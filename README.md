# Ruby Roo! Iteration Practice

The code found in the Dog.rb file is a Dog class with a multitude of class methods that filter and transform `Dog.all` for various purposes. Unfortunately, the author of these methods used `.each` to accomplish the iteration in all cases, when `.map` (or `.collect`), `.find`, or `.select` would have been a better choice. Read the code, run it with some test data (use run.rb!) and understand what the methods are doing. Refactor to use a different array method.

### STEP 1
Read through ALL of the Dog class methods.

### STEP 2
Create a few Dog instances inside of the run.rb file. Use these instances to test the methods out to fully understand what each one is doing.

### STEP 3
Start refactoring! The goal of this assignment is to pick a different (and better) iterator than `.each` to accomplish the same result as the original class method.

### TIPS
Take a look through the Ruby Enumerable docs [here]!


[here]: https://ruby-doc.org/core-2.2.3/Enumerable.html