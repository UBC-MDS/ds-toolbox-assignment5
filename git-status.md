Definition: git status
1. What is the git status command useful for?
The git status command is a quick way to check whether the local and remote repositories are synchronized, and if they are not, it tells you whether the local repo is ahead
 or behind the remote repo. The command also tells you your current branch and lists any untracked files in the branch.
2. How can you access the same information provided by this command if you were using the Jupyter lab IDE instead of the terminal?
You can access the same information in the Jupyter IDE by navigating in the file explorer into the local git repository, opening the git extension, viewing the branch you are currently in (listed just below the repo name), clicking on the Changes tab beneath the branch name, and opening dropdown tabs inside to see the number of Remote Changes, Staged, Changed, and Untracked files.
When you open the Remote Changes dropdown, if you are behind there will be a small "B" and a "+" on the tab that allows you to pull. If you are ahead of the remote repo, you will see an orange dot next to the cloud symbol with an up arrow in the header. This tells you that you should push to the remote repo. The cloud with a down arrow next to it is a symbol for pulling.
