Setting Up Your Project’s GitHub Repository
As mentioned in the introduction to Git, you’ll want to organize all your projects like a portfolio and link them to GitHub so it can be seen by others.

If you do not know how to set up a repository, follow the instructions found in Git Basics to learn how.

Create a new repo for this project on GitHub.com and call it odin-recipes.

Move that repository onto your local machine, inside the repos folder that you previously created in the Git Basics lesson. The command should look like git clone git@github.com:username/odin-recipes.git (use SSH).

Now cd into the odin-recipes project directory that is now on your local machine.

Set up your README.md file and write a brief introduction describing what the current project is and what skills you will have demonstrated once you have completed it. (You can also do this as a self-reflection at the end of the project, which is a good way to review what you have learned.)

If you are having trouble:

All Git commands need to be run from inside your project’s folder (did you forget to cd into the odin-recipes folder?).

Ensure you followed the steps here on Step 2.3 to clone from GitHub with SSH.

Refer to the workflow in the Git Basics Lesson.

Tips on When to Commit
Don’t forget everything we went over in the previous lesson about commit messages!

When you’re building your project, you will probably end up doing several git add + git commit cycles before being ready to push it up to GitHub with git push origin main.

When writing code, it’s considered best practice to commit early and often. Commit every time you have a meaningful change in the code. This will create a timeline of your progress and show that your finished code didn’t appear out of nowhere.

After you have entered git push origin main, switch over to your browser and open your repository on GitHub. You should now see all the files you just pushed.

Okay, that’s enough Git for the moment – time to actually build stuff!

Assignment
Iteration 1: Initial Structure
Within the odin-recipes directory, create an index.html file.
Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.
Iteration 2: Recipe Page
Create a new directory within the odin-recipes directory and name it recipes.
Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use here.
For now, just include an h1 heading with the recipe’s name as its content.
Back in the index.html file, add a link to the recipe page you just created. Example: Under the <h1>Odin Recipes</h1> heading, write out the link like so: <a href="recipes/recipename.html">Recipe Title</a>. The text of the link should again be the recipe name.
Iteration 3: Recipe Page Content
Your new recipe page should have the following content:

An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or the recipe site we linked to earlier.

Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.

Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.

Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

Iteration 4: Add More Recipes
Add two more recipes with identical page structures to the recipe page you’ve already created.
Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.

Viewing Your Project on the Web
If you want to show your work (the project) to others, or submit a solution below, you will need to publish your site so that others can access it from the web, rather than just on your local machine. The good news is that if you have your project on GitHub (as described above), doing this is incredibly simple.

GitHub allows you to publish web projects directly from a GitHub repository. Doing this will allow you to access your project from your-github-username.github.io/your-github-repo-name.

There are a couple of ways to go about doing this, but the simplest is this:

make sure that the main HTML file of your project is called index.html. If it is not, you will need to rename it.
go to your GitHub repo on the web.
click on the Settings button from the panel at the top.
click on Pages on the left side bar.
change the Branch from none to main branch and click Save.
it may take a few minutes (the GitHub website says up to 10, but we’ve seen it take up to an hour. Do not add a “theme” to your project, or you may have git conflicts, instead, be patient.) but your project should be accessible over the web from your-github-username.github.io/your-github-repo-name (obviously substituting your own details in the link)