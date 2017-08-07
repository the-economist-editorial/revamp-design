# Kactus - sketch version control

## Initial setup: ##

* Install Sketch:https://www.sketchapp.com/

* Install Kactus:https://kactus.io/

* Run Kactus

* Click __'clone a repository'__

Enter the repository url in this case:https://github.com/russEco/revamp-design.git
and then set a local path to somewhere that makes sense on your HD.

 * Click __'clone'__

The repository should now download to the local path that you set.

___________________________________________________________

## Working with existing sketch files ##

You should now see a list or at least one sketch file listed on the left.

Click on a chosen file and select __'regenerate sketch file'__

You should now be able to click __'open file'__ on the left of regenerate sketch file option, click this and the sketch file should open in sketch.

You can now edit the file but be aware you are editing the file in what's known as the master branch which is the default version created when you initialise a git project.

Ideally you should work on your own version on a personal branch, which is effectively a copy of the master branch. You should make your edits in this branch and then when your happy merge these back to the master branch. This basically insures that changes can be triaged before merging them.

___________________________________________________________

## Creating a branch ##

You should see in the top navigation in Kactus 'current branch' which should have 'master' listed.

Go to the app menu bar at the top of the screen and select 'branch/New Branch...'
You will be asked to create a branch name, name it something that pertains to your change something like 'font-changes' for example (no spaces in branch names are allowed).

Click __'create a branch'__

You should now see the branch name you created is selected in the current branch option.

Click __'Open file'__ on the main screen.

You can now make you edits inside the sketch file.

When you are done select __'File/Save'__ in sketch.

## Committing a change ##

Return to Kactus and you should see in the bottom left a list of changed files, there might appear to be more changes than you thought but this is just because Kactus breaks down the file to create the changes git needs to track. So you may have just changed a font but it will list 100's of changes, this is fine just ignore the amount.

The changes should be selected by default if not select all the changes with the checkbox at the top.

In the summary field below add a message that is relevant to the change something like 'header font changes' for example. This is whats known as the commit message and lets others know roughly what the change was about.

Click the green button at the bottom __'Commit to ... '__

Click __'Publish branch'__ in the top menu.

______________________________________

## Creating a pull request ##

You have now published your branch to the remote repository on github, in other words you have uploaded your proposed changes to be added to the master branch or master sketch file.

Now we need to create a 'pull request' this basically sets up a staging point where the changes can be checked.

In Kactus select __'Branch/Create pull request'__. This will open a pull request in Github. Click the green button __'Create pull request'__.

______________________________________

## Merging and pushing the change file ##

We now need to merge the pull request.

Return to Kactus

In the current branch option switch back to the master branch buy going to the top menu and selecting __'Branch/Merge into current branch...'__

Select the branch to be merged and click __'Merge into master'__

In the main menu at the top left click __'Push origin'__ this will push uploading your changes to the repository effectively saving your changes so that other team members pull and download the changed sketch file.

_________________________________________

## Best practices ##

Always close any old open file in Sketch.

When ever you return to work on a file first go to Kactus and select the option on the top right 'Fetch origin'
This effectively syncs your local file with any other changes that might have been committed by anyone else.

Select the sketch file and click __'Open file'__ in Kactus.

Repeat the process above to make your edits.

_________________________________________

## Creating new files ##

In the list of files in the left click the __'+'__ button, name and create the file.
Select the new file on the left and click __'Open file'__.

Edit and create your design in sketch when you done save the file in Sketch.

Return to Kactus

You should see on the left a list of changes. Repeat the commit process above and click __'Push origin'__ to push or upload your new sketch file. Ideally you should repeat the process of creating a new branch when doing this but not really necessary when it is a new file.

When editing the new file once it has been pushed please repeat the editing process above by first creating a branch.

__________________________________________

## Other points ##

Remember when pulling new sketch files you may need to click the __'regenerate sketch file'__ option before being able to open the file in Kactus.
