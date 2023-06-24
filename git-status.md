# Definition: git status

Running the command ```git-status``` allows the user to view information about the current state of the working folder. The command will output information about:

* the current branch;
* whether or not the local folder is in sync with the remote repository;
* local files that are staged but yet uncommitted;
* local files that are tracked and modified but not yet staged;
* local files that are untracked.

Information may be viewed through the terminal, and also within the Jupyter IDE. In Jupyter, the Git sidebar provides a visual representation of the current state of the working folder, and compartmentalizes information into specific section, e.g. 'Staged', 'Untracked', etc. Unlike ```git-status```, the Jupyter IDE also allows for information about the commit history to be viewed.