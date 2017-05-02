# Greenpeace_quiz  option #1
The Assignment from Greenpeace for Front-End dev application.
The quiz application uses of Bootstrap and Jquery Frameworks to ensure a good functions extensibility and code reusability.
I tried to maintain the UI as clean as possible (for better integration in different websites or pages), but consistent with Greenpeace's colors and branding-identity.
Initially the Categories of the quiz are collapsed, by clicking on a Category name the user can select one or more items under that category.
Once the user select at least one option the panel heading changes the style for indicating the user that something is selected inside, this can be useful for closed panel categories. The code is quite extensible, for adding more categories we can simply add a category block in the page and change the global variable "total_categories" witch indicates the number of categories that are present.
There are three main functions in the page: highlightItem() witch changes the UI on the basis of what is happening on the page, getSelection(cat_id) witch prints the name of items that are selected by the user for a given category, and showResults() witch collects the selected options and show the result to the user inside a Modal Panel.

This web application could be easy implemented also as a Wordpress Plugin and inserted in every page simply with a shortcode (something like [greenpeace_quiz]).
 
