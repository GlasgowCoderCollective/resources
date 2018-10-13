# Resources
I'm borrowing a lot from github docs for this writeup.

##Fork the repo
1. Fork this repository with the Fork button on top right of screen.
2. You should now have a copy under your name ie yourname/resources.

##Create a local clone of your fork
1. Navigate to your fork of the project.
2. Select the dropdown on the green clone or download button and copy the url.


3. In command line type the url:
   git clone https://github.com/yourname/resources.git


4. Change directory into your project:
   cd resources


##Set an upstream pointing to the original project
1. git add upstream https://github.com/GlasgowCoderCollective/resources.git


2. You can check the remotes are set correctly with:
   git remote -v

3. It should print something like this:
   origin  https://github.com/yourname/resources.git (fetch)
   origin  https://github.com/yourname/resources.git (push)
   upstream        https://github.com/GlasgowCoderCollective/resources.git (fetch)
   upstream        https://github.com/GlasgowCoderCollective/resources.git (push)

##Check for changes
 1. You should check regularly to see if there's any changes in the original code by fetching them
    git fetch upstream

 2. Checkout your fork's local master branch
    git checkout master

 3. Merge any changes from upstream/master to your local master branch.
    git merge upstream/master

##In your code editor
 1. Make changes in the index.html file adding your link to some helpful resource, copying the entire links div and editing to include       the url and some descriptor.
 
 2. Save any changes


 ##Back in command line:
 ##Add and commit
 
 1. git add index.html

 2. Now make a commit
    git commit -m "add my link"


 At this point you've got your changes on your local copy of the code (on your computer) and you've told git about it by adding and committing.
 Next you want to push the changes up to your remote copy (your fork on github). 

It's a good idea to redo the check for changes section to include anything and avoid problems.

##pushing to your remote
1. git push origin master

Your code should now be pushed to your remote.  

##To do a pull request 
1. In github in your fork, refresh if it was still open.

2. Select the "new pull request" button.
