Homework
Look at the snakes and ladders sample solution.
Find out how to run the game (it should print out results to the terminal).
Try to draw a class diagram of this solution.
Think about the following questions and bring your answers for tomorrow's homework review.


Questions to consider:

What is different from the way you tried to solve the problem?
We've had a x_spec.rb file for every x.rb file, but this doesn't.



Are there any parts you don't understand?
I understand what the viewer class is doing, but why doesn't it need to be initialized?
I don't understand the turn log
What is the run_specs.sh file doing?



Testing - why has the dice class not been tested?
Because the result is random due to .sample so we can't enter a value for expected



Why is all of the 'puts'-ing in one viewer class?
This is the class file that is interacting with the player through the terminal. We want all the interactions in one place so that we don't need to run multiple files
