# group67RecipeApp

## Description of the problem domain:
Cooking varied and healthy meals, dietary preferences as well as nutritional awareness have become an important part of our daily lifes. The sheer abundance of recipes on the web as well as taking several aspects such as diet, nutrients, intolerances and available ingredients into account, makes it difficult for many people to find sutitable recipes for everyday cooking.
As a result, we decided to work on a project which revolves around food, nutrition, and recipes. Our project plans to address the common kitchen dilemma of deciding what to cook with the available ingredients on hand. We plan to solve this issue by giving users an easy way to get recipes based on individual preferences, nutritional values, and the ingredients they have at home.

## Description of application:
The idea is to create a helpful recipe discovery and nutrition application.
Users can input the ingredients they have, and the app will provide a selection of recipes that can be prepared using those ingredients, reducing food waste and encouraging creativity in the kitchen. Users can select from a variety of meal types, such as breakfast, fingerfood, main course or snack.
Furthermore, the app allows users to specify dietary preferences and restrictions, such as vegetarian, gluten-free or vegan. 
On top of that, users can specify certain intolerances, such as dairy, peanut or soy. It then tailors recipe suggestions accordingly, ensuring that users can easily find recipes that align with their dietary choices or intolerances. 
Users can set personalized macronutrient goals, such as protein intake between 10g and 30g. The app will recommend recipes that meet these goals, enabling users to achieve their nutritional targets.

Summarized, the application provides the following functions:
* Search and suggest recipe ideas based on specific ingredients given by the user 
* Search and suggest recipe ideas based on specific diets that the user indicates
* Suggest a recipe based on specified macro suggestions
* Provide basic nutritional content about any recipe or ingredient
* Optional: keep track of ingredient usage and create a shopping list

## Link to the documentation for an API:
https://spoonacular.com/food-api/docs

## Screenshot of using a tool to try out the API:
<img width="1067" alt="find-recipe-by-ingredients-screenshot" src="https://github.com/Nina2811aw/group67RecipeApp/assets/77638087/f8faf993-b7eb-484b-93e4-5b031d9fbc75">
<img width="1062" alt="analyse-recipe-screenshot" src="https://github.com/Nina2811aw/group67RecipeApp/assets/77638087/37d57cf3-9770-4173-b7e1-a752931022b5">

## Example output of Java code:
![](/Users/arielkhait/Downloads/Screenshot_2023-10-01_at_18.18.29.png)
## List of any technical problems blocking progress:
Problem: IntelliJ did not recognize when I imported okhttp, and json. 
Solution: I made my project a Maven project and added dependencies in the pom.xml file.
