Github Workflow and Structure:

All edits are created in the Working Directory (these changes are not tracked by git).

The code editor can then `git add .`, `git add [filename]`, etc. At this point get starts tracking changes.

When files are added, they are then considered to be in the Staging Area.

The code editor can then `git commit -m "[message]"` to signify to themselves and to other collaborators what the intention of the commit was (bug fix, new push to a feature, etc.). At this point each commit is given a reference ID from the medidata).

The code is now commited and `git push origin master` will push the stages changes to the repository.
