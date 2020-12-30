# sturdy-train
Indie Developer working on a brand new project and having a blast doing it! #anotherdungeoncrawler #indiedev #gamedev #pixelart

# indie developers are gay.... gottem

# Commands

### git clone link
replace the link with the github link to the repository.
This command is exectued only once, to create the folder on a machine that does not yet have it.

### git pull
used to pull changes from github to computer. use this whenever you want to update home with changes from multimedia or vice versa. Also use after merging a pull request. Basically anytime whats on the computer is not up to date with what is on github.

### git push -u origin branchName
This is how you put changes you made on the computer onto github. Replace branchName with whatever branch you are commiting on. Probably gonna be main 99% of the time.

### git checkout -b branchName
git checkout is used to switch between branches. The '-b' 
flag is only used when you are switching and creating a NEW branch. If you are switching between existing branches do _not_ use -b. 

### git branch --show-current
prints the current branch that you are on to the terminal so you know where you are. Useful sometimes.

### git merge
Used to merge branches together. This is the quick and dirty way, rather than using pull requests. Use this in a scenario such as: 
You create a new branch to reorganize and test something out without affecting the main branch.
Once that branch works, you want to merge it into the main branch. That woud be accomplished like this: 
###### git checkout main
(switch back to main branch)
###### git merge branchName

## git rebase -i HEAD~#
Don't think you'll need this, so for now its forbidden knowledge. Don't use it, but if we need it in the future I'll show you how.
