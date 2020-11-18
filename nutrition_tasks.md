## Week of Nov. 16 - Nov. 30
### Athena
- [ ] graphing logs
  - [ ] Figure out asynchronous querying using JS-created http requests
  - [ ] Line graph showing consumption of nutrients for each day (Chart.js)
    - [ ] Able to choose between multiple nutrients
    - [ ] Able to choose time span of current week, month, or year
    - [ ] Clicking on a marker takes you to detail page
Extra subtasks:
- Time span options include past 7 days or past 30 days
- Display the "goal range" on the graph (depends on completion of others' tasks)
- (Unrelated to graph) Log detail page: add an "add log" button that auto-fills date field

### Bryce
- Recipe Cloning
    - [ ] Have the fields of the clone page initialize to the source recipe's values
    - [ ] Button available from detail view

- Recipe Form
    - [ ] Make it so that it isn't hard-coded which rows are cloned by the Add another Food button

- Personal Recipe List
    - [ ] Shows most of the information that the recipe search results manages to show

- Foods show a list of recipes which contain them as an ingredient
    - [ ] In the nutrifacts view, include a list of public recipes and personally owned recipes which contain that food as an ingredient
    - [ ] Shows most of the information that the recipe search results manages to show

### Tsion
- Pi-chart modification
  - [ ] Removing the sodium from the pie-chart
  - [ ] Converting the rest of the nutrition fact from gram to calorie (Pie-chart will display the nutrifact in calorie)
  - [ ] Add a form where user can add their daily calorie goal (User can be able to add their cal goal in their profile)
- homepage revamp
  - [ ] Remove “How it Works” page and add an updated version of that info (right now it's still about our prototype) to the homepage with our names and stuff
  - [ ] Add links to and explanations of main features to homepage (logs, recipes)
  - [ ] Add signup/login form to the homepage if you aren’t signed in
    - [ ] Easiest way: Add UserCreationForm to context and template, then a button/link that says something like "Already have an account? Sign in here" that takes you to the login page

### Michael
- [ ] Make column headers clickable in search recipe and search food to sort search results (User can order the search results by clicking the column headers)
- [ ] Search filter for food and recipe to search for food with calories between two amounts (User can input desired caloric range when searching food and recipes)
- [ ] Search filter for recipe to search for recipe containing a specific food (User can search recipes that contain a specific food)

### Jalen
- front-end changes
  - [ ] Re-color and/or re-arrange text fields that are difficult to see
  - [ ] Resolve more html/css bugs 
  
### John
- Remove ability to access recipe page when not logged in
  - [ ] Recipe creator should require login to view. Currently it can be accessed but doesn't show any foods.
  
## Week of Nov. 9 - Nov. 11
### Bryce
- [x] Quality of life changes to recipes and foods
  - [x] Foods show a list of recipes which contain them as an ingredient (In the nutrifacts view, include a list of public recipes and personally owned recipes which contain that food as an ingredient)
- [ ] Recipe cloning
  - [ ] Have button in detail template to clone an existing recipe
  - [ ] Have functionality to clone an existing recipe
  - [ ] If it's a public recipe, the resulting clone is a private recipe
- [ ] Recipe form validation
  - [ ] Validate so it doesn't create/update if the new version has two of the same ingredient
  - [ ] Make it so that it isn't hard-coded which rows are cloned by the Add another Food button
- [ ] Personal Recipe List
  - [ ] Shows number of ingredients of each item
  - [ ] Shows calories per serving of each item
- [x] Detail view's delete button should have an "are you sure?" popup

### Athena
Incorporate recipes into logs:
- [x] Add recipes to log functionality:
    - [ ] Add MealRecipe table (models, migrations, db)
    - [ ] Add RecipeAutocomplete (views, urls)
    - [ ] Update get_total() for MealLog and DailyLog (models)
    - [ ] Update LogForm (forms)
    - [ ] Update LogCreate and LogUpdate (views)
    - [ ] Update JavaScript (templates)
        - [ ] Add and remove recipe fields
        - [ ] Change from hardcoded rows to parentElement
- [x] When creating log, must have either at least one food or at least one recipe (forms, clean())

### Michael
- [x] Recipe can have multiple allergies or diets attached to it
- [x] Recipe search displays multiple allergies/diets correctly
- [x] Can filter searches based on allergy/diet
- [x] Search filter defaults to allergy/diet preferences attached to current user's profile

### Jalen
- [x] address cropping issues created by the new navigation bar
- [x] update tables in the search pages

### Tsion
- [x] Add pi-chart to admin page

### John
- [x] Recipe creation can only be seen if logged in.
- [x] Got rid of gram in recipe ingredients list.
- [x] Signup page text has been fixed.
- [x] Added a couple spaces under the nav bar.
- [x] Added more to db, fixed margin on bottom of table to add some space.

## Week of Nov. 2 - Nov. 9
### John
- [ ] fix database values
- [ ] ongoing: add more foods to database

### Bryce
- [ ] Recipe update view
  - [ ] User can add new ingredients to an existing recipe
  - [ ] User can remove existing ingredients from an existing recipe
  - [ ] User can change the portions of an existing ingredient in an existing recipe

- [ ] Recipe detail view
  - [ ] Make sure that the nutrition information is calculated correctly
  - [ ] Figure out a better looking page layout

- [ ] Recipe list view
   - [ ] Some recipe information shown in list view

- [ ] Recipe delete view
   - [ ] Either allow users to delete recipes without leaving their current page, or make the delete recipe template look presentable


### Michael
- [x] Public user-created recipes can be searched and viewed by other users 
  - [x] RecipePreset model removed
  - [x] Option on create/edit recipe pages to make a recipe public or private
  - [x] Searching recipes searches for recipes created by current user and recipes flagged as public
  - [x] Users not able to edit or delete other user's recipes
  
### Athena
- [x] Finish log updating functionality
  - [x] Delete foods from log
  - [x] Errors display properly
  
### Tsion
- [ ] Add Pi-chart in admin to visualize nutrition fact
  - [ ] convert the sodium and cholesterol units to gram to match
  - [ ] display the food nutrition fact in pi-chart in admin page for visualization
- [x] make the page look more clean and organized

### Jalen
- [ ] Update UI
  - [x] Alter certain html elements to help improve the ui
  - [ ] add dropdown menu's to stacked columns

## Week of Oct. 26 to Nov. 2
### Michael
- [x] Update metric/imperial conversion
- [x] Update profile form includes fields in user account model (email, first name, last name)
- [x] When searching for foods/recipes, the results are displayed in pages if there are over a certain amount

### Athena and Tsion
- [x] List of daily logs page
- [x] Details of daily log page
- [x] Edit meal log page

### Bryce and John
- [x] Recipe update view
- [x] Recipe model
- [x] Recipe display view

### Jalen
- [x] Add the search bar back to the navigation bar (missing test cases)
- [x] Link radio buttons to search bar that'll allow you to choose either a recipe or food search (missing test cases)

## Week of Oct. 19 to Oct. 26
### Bryce and Jalen
- [x] Recipe creation view
    - [x] User can name their recipe during recipe creation.
    - [x] User can insert more than one ingredient during recipe creation.
- [x] Recipe list view
    - [x] User can see a list of their recipes.
- [x] Recipe detail view
    - [x] User can see the contents of an existing recipe.

### Michael
- [x] User profile form should only be editable by the user in question
- [x] Metric unit option should convert height/weight between imperial and metric
- [x] Form should be in a table

### Athena
- [x] Change the food input from dropdown select to search by text
- [x] Instructions for setting up the site on an AWS server

### Tsion
- [ ] User can view their logged information he/she submitted

### John
- [x] Add a way to specify what diets a recipe would work for and what allergies to be aware of


## Week of Oct. 12 - Oct. 19
### Jalen
- [ ] Recipe search [issue](https://github.com/COSC481W-2020Fall/cosc481w-581-2020-fall-nutrition-helper/issues/91)

### Bryce
- [ ] Recipe maker [issue](https://github.com/COSC481W-2020Fall/cosc481w-581-2020-fall-nutrition-helper/issues/87)
- [x] Fixing the profile update page (*missing an issue link*)

### Michael
- [x] Making the profiles autogenerate alongside users (*missing an issue link*)
- [x] Allergies/diet preferences #88

### Athena and Tsion
- [x] Daily logs #89

### John
- [ ] <s>Subcategories for preparation method and brand and such things like "Egg, scrambled" or "Chocolate bar, Hershey's" #37</s>
- [x] added fdc ids to the database

