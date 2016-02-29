1. What is the difference between new and create for a model?

New creates an instance of the object stored in the model but does not save it into the DB. Create automatically stores the object into the BD.

2. What command combined with new will emulate the same behavior as create?

The save command will save the new object into the DB

3. What is the column that exists on every table but we did NOT define?

created_at and updated_at

4. What single line of ruby code can insert a cat with the name "hat" in the database?

Cat.create(:name => 'hat')

5. What was the most confusing part over the last few weeks?

Kind of at a high level, where do we put ruby logic that does more complicated calculations? There are things that I've seen in the .keep file but why there? Is the ruby logic always contained in there? Or is there somewhere else that most ruby logic is held?

6. How did you like this homework in comparison with the others?

This one was rather short, not bad, but didn't learn too too much. It would be good to move perhaps a bit faster?
