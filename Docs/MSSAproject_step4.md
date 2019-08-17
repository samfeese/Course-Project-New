#High level Requirements Explained.

##Functional

###built in list of food ideas (basic)
1. Upon clicking a desired meal (breakfast, lunch or dinner), system randomly selects a stored basic food menu item, displays it to the user and asks if they want to 'roll' again.
2. Upon clicking "no" to the repick, system presents option to find a recipe.
if the user wants to roll again repeat step 1.

###database of recipes/database pull
User decided to get a recipe, this can work one of two ways. database stores actual recipes, or store hyperlinks to top rated recipes, so system picks a random recipe, and displays it to user - or directs user to link using default browser.

###Step by Step
	User decided on a recipe, system presents recipe all at one, then goes into a step by step instruction. With "how to" videos for the basic tasks, such as, whisking, kneeding pizza dough.
	user flips page to next step when they get there.

###recipe builder

User inputs items that they have, system takes input, pulls items that match at least 1 parameter and list to user by relevance- all ingredients at top, 1 match at bottom;

###Tags

User inputs a tag for what they are craving/would like to make such as, pasta- system takes input and searches all food on database and outputs in a list the food. 
input == pasta; output == lasagna, spaghetti, ravioli, chicken Alfredo, beef strogganoff, pad thai, etc. displays 10 per page. Difficulity ranges added here too.



User can add tags to items as well. like tag quiche as breakfast. or as pie.

###Filters

User clicks filter tab/button system displays filter tab; user checks filters, and saves to searches
items in filter, Difficulty level; allergies; cooking capabilities(if have oven, stove, micro) cold or hot food.


##Non Functional



###Easy User Interface:
With a basic GUI, User clicks button options "A, B, C etc. (still not sure what they will be)" and once button is clicked, system directs user to next page, where another menu is displayed asking what meal or what ingredients.
 
