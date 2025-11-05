There are key differences between each of the commands merge, rebase, squash, and cherry-pick.

Merge seems to just combine the 2 branche's commits together into 1 additional commit on the current branch. This is useful when you want to preserve the edit history of the project.

Rebase, instead just "moves" a commit from 1 branch to another, keeping a commit message the same. Rebasing seems to be better for keeping the repository clean, and having a more linear flow.

Squash is useful for when there are lots of unnecessary commits and you want to simplify the flow. This could be useful if there's someone on the team with confusing commit messages.

Cherry-pick could be used if you have a specific feature from one commit that is useful in another branch. Could be used if there are parts of a branch that are operational and other parts that are still in development.

feature1's branch seemed to be pretty straight forward changes with simple, minor edits - but it would be useful to see the history.

feature2's branch showed a little more complicated commits and demonstrated that rebasing can be used to simplify the commit history.

feature3's branch was the most confusing, mainly because of the commit messages that didn't provide any real context, and this showed why squash is necessary.