# GitHub Flow Demo

Use this template repository to practice GitHub Flow. 

## GH Flow Hands-On

One team member creates a private repo using this template and adds the second team member to the repo as a collaborator.

Team Member 1 adds Issue #1 “Define function for area of a sphere” and assigns it to Team Member 2.

Team Member 1 adds Issue #2 “Define function for area of a circle” and assigns it to themselves.

Now complete the assigned task using the following steps:

- Clone the repo from the command line using ```git clone <URL>```
- Create a new branch with the title of your issue using ```git checkout -b <branch_name>```
- Open a text editor and add the code in line 11 of your script. Save your changes.
- Commit your changes from the command line using ```git commit -m "your message here"```
- Push your changes to the remote branch using  ```git push -u origin <branch_name>```
- Create a pull request. Make sure to mention in the description that your pull request closes the respective issue using "Closes #number-of-your-issue"

Team Member 1 reviews Team Member 2’s PR, merges, deletes branch, and closes the PR. 

Pull up the Issues. Is Issue #2 closed now?

Team Member 2 reviews Team Member 1’s PR, and UH OH! Conflict!! Team Member 2 fixes it on GitHub using the editor. Merge, delete branch, and close the PR.

