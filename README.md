# resources
I'm borrowing a lot from github docs for this writeup

## Fork the repo
Fork this repository with the Fork button on top right of screen  
You should now have a copy under your name, i.e. yourname/resources

## Clone your fork
Navigate to your fork of the project  
Select the dropdown on the green clone or download button and copy the url  
In the command line type:  
`git clone https://github.com/yourname/resources.git`


Change directory into your project:  
`cd resources`


## Set upstream
Set an upstream remote pointing to the original project:  
`git remote add upstream https://github.com/GlasgowCoderCollective/resources.git`

You can check the remotes are set correctly with:  
`git remote -v`

It should print something like this:  
```
origin   https://github.com/yourname/resources.git (fetch)  
origin   https://github.com/yourname/resources.git (push)  
upstream https://github.com/GlasgowCoderCollective/resources.git (fetch)  
upstream https://github.com/GlasgowCoderCollective/resources.git (push)
```

## Check for changes
You should regularly check for any changes in the original repo by fetching them with:  
`git fetch upstream`

Checkout your fork's local master branch with:  
`git checkout master`

Merge any changes from upstream/master to your local master branch:  
`git merge upstream/master`

## In your code editor
Make changes to the index.html file adding your link to some helpful resource, copying the entire div and editing to include the url and some descriptor  
Save any changes


## Add and commit

`git add index.html`

Now make a commit:  
`git commit -m "add my link"`

At this point you've got your changes on your local copy of the code (on your computer) and you've told git about it by adding and committing  
Next you want to push the changes up to your remote copy (your fork on github). It's a good idea to redo the "check for changes" section to include anything and avoid problems

## Push to your remote
`git push origin master`

Your code should now be pushed to your remote.  

## Submit a pull request 
On GitHub, in your fork, select the "new pull request" button






