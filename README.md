# Burger2

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.
Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.
The app will store every burger in a database, whether devoured or not.

# Replacing my MySQL Burger model with a Sequelized equivalent.

Added validations to the models where:

A burger's name cannot be null
A burger's devoured status is false by default
A Customer's name cannot be null

Order the Burgers you send back to the user in alphabetical order using the Sequelize "order" option.
