# GenAI-Recipe-Recommender-w-Ingredient-Database-Optimization
GenAI - Recipe Recommender with Ingredient Database Optimization
Capstone Project: Google x Kaggle GenAI 5-day Intensive Course, 2025
April 20th, 2025
sophia.t.hart@gmail.com

The Problem
Meals are important—for the creativity in planning and cooking, the joy of eating good food (especially if you are sharing it with your loved ones), and the nutrients they provide for healthy living. For quality living, we like fresh ingredients and exploring recipes. This does not come easily with time constraints. In this project, I built a database of ingredient inventory specific to the household. After taking the Intensive 5-Day GenAI course that Google and Kaggle put together, I attempted to apply GenAI to solve this optimization problem. I built a GenAI agent to interact with the ingredient database. If there is a recipe database, this application would call the other agents, apply optimization techniques, and recommend a recipe to a chef.

Use Case
This application's purpose is for families and individuals to eat healthily at home daily; however, it can be generalized to be used in restaurants with different customers if the restaurants have chefs with diversed cooking talents.

The user's ingredient inventory is stored in a database. The GenAI agent converses with the user to evaluate the user's meal preference on that day/moment, looks at the user's inventory, and plans a meal for the user. The inventory input can come from three different sources: 1. The user inputs one item at a time using a UI that interfaces the database. 2. The user provides the store name. When the items are checked out, if the store has a partnership with the owner of this app, the checked-out items will be stored in the user's database. 3. This applied to both in-store and online checked-out, although online may have a different interface rather than providing the store's name.
