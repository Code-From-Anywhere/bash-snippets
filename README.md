# Code From Anywhere CLI snippets

## ship

Ship is a small cli command I wrote that automatically adds and commits all your changes and pushes them to your current branch.

To add ship to your cli, copy and paste this into your terminal:

`echo "ship () { BRANCH=$(git branch --show-current); git add . && git commit -m \"${1:-Improvements}\" && git push -u origin \"$BRANCH\" && say you shipped it || say something went wrong }" >> ~/.zshrc && source ~`

## alias

This is to make an alias to quickly execute some command, for example, going to a certain folder you have to go to a lot.

`alias xyz='cd /Users/youruser/Documents/yourfolder'`
