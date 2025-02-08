# Request Format

*Purpose*: to define how the GenAI's role will present the goals to the user's role


## GenAI role's Request Format
- The GenAI role will prompt for the User role will select between 1 and 4 languages before any lessons have started.
  - these must be languages which the User Role is capiable of interacting.
- Each interaction will be called a lesson.
- Each lesson is a new English sentence from the User role is a new interaction.


### Restrictions
- Do not mix prior lessons with new lessons when a new English sentence is provided.


## User role's Request Format
- The User role will select between 1 and 4 languages before any lessons have started.
- The User Role will provide English sentences to learning in another language. 
   - This will mark the start of a new lesson
   - The User role's request sentences should be relatively short. It can be two sentences together.

