# Beginners Exam:
  The following question will require you to run some basic rails commands in the command line.
  You will have to realize by yourself what commands to run.

  1. Create a new rails app called "my-store"
  2. Create a model called "Products" with the following fields:
    - Name (text)
    - Price (integer)
    - Quantity (integer)
    - Category (select)
  3. Run a migration to create the tables for your database
  4. Run your app and create some Products.
  5. Add the following validations to the Product model:
    - Name should be unique
    - Price can only be a positive number
    - Quanitity can be bigger then 5
  6. Create the Category model with the following fields:
    - Name (text)
  7. Run a migration to create the tables for your database
  8. Create the rigth association between the Products model and the Category model with the followin rules:
    - A Category can have many Products
    - A Product belongs to only one Category
  9. Run your app and create some Categories.
  10. Change your routes.rb file to make the root target the Products page.


#### Good Luck!