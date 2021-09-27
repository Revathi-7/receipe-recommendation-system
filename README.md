# receipe-recommendation-system
 Data-driven recipe recommendation system using web-scraped recipe data (including but not limited to data like ingredients, health facts, etc.) and user’s historical preference. 
 recipe_info.csv: the recipe 'name', 'type' (e.g., Breakfast and Brunch), and 'subtype' (e.g., Pancake Recipes). Also contains a column for each GMM-produced cluster labels. For each of the feature-reduced datasets, there are cluster results for 4, 25, and 54 components.
recipes_normalized_varFS_extraTrees186.csv: set of ingredients chosen again (from previously derived set) by an identical ensemble classifier, with a size of (61880, 186)
recipes_encoded100.csv: recipe dimensions were reduced from 7000+ to 100 using a stacked autoencoder of hidden layers 1000 and 100. Input Set: recipes_normalized_varFS.csv. Output Size: (61880, 100)
