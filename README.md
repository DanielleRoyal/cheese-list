# cheese-list
Create the project directory

Go to your command line (Terminal for Mac, Git Bash for Windows).

First, let’s make sure we’re in the right directory: pwd.  If not, cd to the directory we want our project to live in!

We should ALWAYS put our project in its own directory.

Create the directory with the command mkdir cheese-list. Then cd cheese-list.

Inside the directory, create a single text file: touch cheeses.txt.

Open the directory with the command code .

Assuming you were in the cheese-list directory, you should now see the directory open in VS Code.  Great job!

Initialize the repo

You know what to do! git init. Yep, it’s that simple.

Open the directory in VS Code

On the command line, run code . to open the directory in VS Code.  If this command isn’t working for some reason, you can open the directory manually by clicking in VS Code:  File > Open Folder…

Add Cheese

Open the cheeses.txt file we created above, and add some text to it.  It’s not important what the text is, but it’d be fun if it was a list of cheeses.  If you’re not feeling particularly creative, here are a few:

- Cheddar
- Mozzarella
- Roquefort
- Compté
- Fontina

Add to Staging

Run git add . or git add -A In order to add the cheese list to the staging area.

Commit

Run git commit -m “initial commit”.  This is your first commit!

Create the Github Remote Repo

Now, create a brand-new (empty!!) repo on Github.  If you don’t remember how to do that, go back and look at the lessons in the GitHub module. Name the repo cheese-list.

Please make the repo public, so that your coach can look at your work once you’re done!

Add the Remote

Now, if we run git push, we should get prompted that we need to set up a remote!  So instead run… git remote add origin <my-github-remote-url>. For example, if your github username was “bilbobaggins” you’d run something like

git remote add origin https://github.com/bilbobaggins/cheese-list.git

Set the remote tracking branch

OK, but if we run git push again, we still get an error.  This time, it gives us the command right within the error message!  So run git push --set-upstream origin main.  This accomplishes the same thing as git push but also sets up our remote tracking branch.

Note: Sometimes the main branch is called master, and sometimes main. Pay attention to which one is being used!

Commit on GitHub

Now, so that we can have something to practice our git pull command with, we’ll edit a file directly in Github.  This was covered briefly in the demo video, but if you’d like more detailed steps, read the instructions to edit files on Github.  What should you edit?  It would be great to add a new cheese to the list!  Something like “Wensleydale” would be nice.

Pull the Changes

Our final step is to run git pull and you should see your newest Wensleydale cheese listed in your local version (in VS Code)!

Congratulations!  You are officially a Jedi Git apprentice 🎉
