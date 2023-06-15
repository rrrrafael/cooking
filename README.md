# Recipes
## A recipes website

This repository starts off as an assignment project from
[The Odin project](https://www.theodinproject.com/about)'s Foundations Course.
This project serves as a moment of practice and knowledge checking in the HTML
Foundations section within the same course. Here, I am summarizing all that I
have learned in this section, as well in my own research on the web.

This project is divided into four different iterations. The main focus of these
iterations is HTML. There will be later moments where this project will be
revisited for practices of CSS, building upon this early work.

## The assignment

This website is going to consist of a main index page which will have links to
a few recipes.

### Iteration 1: Initial Structure

 - Create an index.html file.
 - Populate it with the HTML boilerplate and an "Recipes" h1 heading.

### Iteration 2: Recipe Page

 - Create a directory recipes/.
 - Create a .html file within the recipes directory naming it after the
 recipe it will contain.
 - Include an h1 heading with the recipe’s name as that file's content.
 - Add a link to the created page inside the index.html file.

### Iteration 3: Recipe Page Content

The recipe page should have the following content:

 - An image of the finished dish under the h1 heading added earlier.
 - An appropriately leveled “Description” heading followed by one or more
 paragraphs under the image.
 - An “Ingredients” heading followed by an unordered list of the ingredients
 needed for the recipe under the description.
 - A “Steps” heading followed by an ordered list of the steps needed for making
 the dish under the ingredients list.

### Iteration 4: Add More Recipes

 - Add two more recipes with identical page structures to the recipe page
 created earlier.
 - Add links to the created pages inside the index.html file. (Consider putting
 all links in an unordered list.)

Example:
```html
 <ul>
   <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
   <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
   <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
 </ul>
```
