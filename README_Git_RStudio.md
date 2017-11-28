The is the Leaf Classification playground challenge from Kaggle.

Using this to demonstrate version control from within R Studio.

Create an R Project first based on this directory - WineCluster.

Then put it under version control from the Tools menu. 
Notice that RStudio creates a .gitignore file for you. Take a look at it.

Then let's make our initial commit. We'll just add the Rmd files, image files, this file and the .gitignore file. 
In other words, we aren't putting the any data files under version control.

After the initial commit, you'll notice that the Push and Pull buttons are greyed out. We don't have an remote repos set up for this project. 

We'll set up a remote at the command line. Let's go back to the SW lesson and
figure out how to do this.

http://swcarpentry.github.io/git-novice/07-github/

Go to your GitHub account and add a new repo called WineCluster. You'll be able
to copy the following commands to the clipboard from GitHub and then
you can run them to push your local WineCluster repo to GitHub.

     git remote add origin https://github.com/<your github account>/WineCluster.git
     git push origin master

Now make some changes to this file and let's do another commit. Then you'll be able to use R Studio to push the changes to GitHub. Go to to your GitHub account and confirm.

