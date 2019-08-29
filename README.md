# Backend-Test
design REST APIs using Django REST Framework

Models:

 

- Design the User Model with username(unique field), email(unique field), first_name,
last_name,m password. (You can use the django inbuilt user model)
 

- Design A Step Model with step_text(string field, not null), Many to One relationship with
Recipe
 

- Design An Ingredient Model with text(not null, string), Many to One relationship with
Recipe
 

- Design A Recipe Model with name(string, not null), Foreign Key to User table(one to one
relationship), One to Many relationship with Step and Ingredient Model
