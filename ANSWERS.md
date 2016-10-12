## Questions

1. What is the difference between new and create for a model?

Create saves the model to the database automatically whereas new simply creates a new instance of the model and we have to save it manually afterwards.

2. What command combined with new will emulate the same behavior as create?
We must use the 'save' command to save.

3. What is the default integer column that exists on every table but we did NOT define?
It is the id column that every new model is assigned

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(:name => "Kira")

5. How did you like this homework in comparison with the previous homeworks?
I thought this homework was a little bit easier because I have a better understanding of Ruby and Rails, but I had some issue with some of the commands like rake db:migrate.