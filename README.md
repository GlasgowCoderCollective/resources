This repository is full of helpful links for people who are just learning to code! Below you'll find the instructions on how to contribute to the list of helpful links. 
If this is your first time coding or you're a veteran who wants to learn something new or just explore, this is the place for you. Dig in and keep adding more resources you find helful during your open source voyage. Happy coding!

# resources

[The current web page we will be adding to](https://glasgowcodercollective.github.io/resources/)  
I'm borrowing a lot from github docs for this writeup

## Fork the repo

Fork this repository with the Fork button on top right of screen

You should now have a copy under your name ie yourname/resources

## Create a local clone of your fork

Navigate to your fork of the project
Select the dropdown on the green clone or download button and copy the url

In command line type the url:
`git clone https://github.com/yourname/resources.git`

Change directory into your project:
`cd resources`

## Set an upstream pointing to the original project

`git add upstream https://github.com/GlasgowCoderCollective/resources.git`

You can check the remotes are set correctly with:
`git remote -v`

It should print something like this:

```output
origin https://github.com/yourname/resources.git (fetch)
origin https://github.com/yourname/resources.git (push)
upstream https://github.com/GlasgowCoderCollective/resources.git (fetch)
upstream https://github.com/GlasgowCoderCollective/resources.git (push)
```

## Check for changes

You should check regularly to see if there's any changes in the original code by fetching them
`git fetch upstream`

Checkout your fork's local master branch
`git checkout master`

Merge any changes from upstream/master to your local master branch.
`git merge upstream/master`

## In your code editor

Make changes in the index.html file adding your link to some helpful resource, copying the entire links div and editing to include the url and some descriptor.
Save any changes

## Back in command line

## Add and commit

`git add index.html`

Now make a commit
`git commit -m "add my link"`

At this point you've got your changes on your local copy of the code (on your computer) and you've told git about it by adding and committing.
Next you want to push the changes up to your remote copy (your fork on github)

It's a good idea to redo the check for changes section to include anything and avoid problems

## pushing to your remote

`git push origin master`

your code should now be pushed to your remote.

## To do a pull request

In github in your fork, refresh if it was still open

Select the "new pull request" button
