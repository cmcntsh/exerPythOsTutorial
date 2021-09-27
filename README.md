# Python OS Module Tutorial

(2021 update: No better tutorials for this topic found.)

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Create a Jupyter Notebook in your repository.
- [ ] Watch the tutorial and execute commands.
- [ ] Push your new files to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
  * A reminder about forking a repository:
  * Forking a repository is copying it from an original GitHub account to your own GitHub account.
  * Forking a repository is done by clicking on the Fork button located at the top, right corner of the main repository page.
  * You can only fork a repository once. If you try to fork a repository on your own GitHub account, you'll get an error message. If you try to fork a repository you already forked (without deleting it on your own account first), you'll also get an error message that you already forked the repository.
* Cloning a repository can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.

## Create a Jupyter Notebook .ipynb file

* 2022 update: Complete the notebook which is included in the repository.
* In Jupyter Notebook or VSCode navigate to your repository folder.
  * Create a new Jupyter Notebook called OSTutorial.ipynb

## Watch Tutorial

* Follow along with Python tutorial: OS Module (20 min): https://www.youtube.com/watch?v=tJxcKyFMTGo
* Execute code examples in separate cells.
  * import os
  * print(dir(os))
  * print(os.getcwd())
  * os.chdir()
  * os.listdir()
  * os.mkdir() - make a new directory folder in the repository
  * os.makedirs() - make a new directory with a subdirectory in the repository
  * os.rmdir() - remove the new directory
  * os.removedirs() - remove the new directory with subdirectory
  * os.rename()
  * print(os.stat())
  * from datetime import datetime
  * print(datetime.fromtimestamp())
  * os.walk()
  * print(os.environ.get('HOME'))
  * os.path.join()
  * os.path.basename()
  * os.path.dirname()
  * os.path.split()
  * os.path.exists()
  * os.path.isdir()
  * os.path.isfile()
  * os.path.splitext()
  * add a comment in a cell with a url for official Python documentation (not shown in the video - Google it)
  * add a comment in a cell with a url for a tutorial on the OS module in the official documentation (not shown in the video - look through the documentation to find it)
  
* When you're done make sure you save your file.

## Push your updated file to your GitHub repository

* This can be done in VSCode.
  * In VSCode click on the Source Control button.
  * You should see the files that had changes. (Mine has the original file which shows an M next to it and a new file which says checkpoint in the name. You really only need to push the original file, but if you push both it shouldn't hurt anything.)
  * Hover over the changed file. Click the + sign to stage the change.
  * Enter a commit message in the message field and click the checkmark to commit the change.
  * Click on the 3 dots for more actions and select Sync. This will push the updated file to your GitHub repository.
  * Submit the link to your GitHub repository on Canvas.
