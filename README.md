
# Recipe-app-api

This is an api base project that users can use to create, delete, update recipies, and add ingredients and tags for the recipes.

## Main Features
- Users must be authenticated
- Create recipes with a tittle, how long it takes in minutes, how much cost to do it and description options.
- Users can tag their recipies (Eg: "Soups":cook:)
- Users can add multiple ingredients in a recipe.
- Users can upload recipe's images and linked to the specific recipe.

 ### Delete, update, and get recipes, ingredients, and tags
 - Delete recipe if user is the owner of the recipe.
 - Ingredients and it will be checked if the ingredient already exist or create a new one.
 - Add tags to recipes and it will be checked if the tag already exist or create a new one. 
 - Update tags and ingredients as partial update and updating the whole object.
 
 ### /me endpoint
 - Users can get their own profile.
 - Users can update password and name.
 
 ## Techs aspects
  - Docker compose
  - DRF (Django rest-framework)
  - TDD (test driven development)
  - Swagger
  - PostgreSQL
  
> Rcipe-app-api
> This is a project I was working on to get more undertanding of ```docker compose``` and teh process to develop a django API usig the TDD aproach.
> The projects idea is legitim to [Mark Winterbottom](https://www.udemy.com/user/mark-winterbottom/):man_technologist: who hepls me to archive this project.
