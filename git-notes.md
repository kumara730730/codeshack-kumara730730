**Basic git commmands**

1. git config --global user.name

Purpose: Sets the name that Git records as the author of your commits. It can be your name or a chosen username. This command does not check whether the username exists on GitHub.

2. git config --global user.email

Purpose: Sets the email address Git records in your commits. It does not register your email with GitHub or verify that the email belongs to your GitHub account.

3. git config --global --list

Purpose: Displays the Git configuration settings saved for your user account on your computer.

*Example output:*
user.name=kumara730730
user.email=kumara730730@gmail.com
safe.directory=*

- user.name: The configured commit author name.
- user.email: The configured commit author email.
- safe.directory=* : Marks all Git directories as safe for Git's ownership checks. This is a separate security-related setting, not part of your name or email configuration.

4. gh auth login

Purpose: This is used to login to your github account in the terminal where the user will use to push files or make changes to his repo. Instructions to login will pop up as you enter this command.

5. gh auth status

Purpose: *"Login active to this account"* We expect this line when the command is run, we can confirm that we have loggined to the required account and if it is actively connected or not.

6. gh repo create repo.name --public --clone

Purpose: This command is used to create a new repository in our github account, to upload files and collaborate. *--public* signifies that it is a public repository. *--clone* is used to clone the repo in the terminal to make changes to the repo as per our requirement.

7. cd codeshack-kumara730730
code README.md
code git-notes.md

Purpose: These commands are to change the directory to the required repo.name to access it and create specific files required.

8. git add git-notes.md
git add README.md

Purpose: Stages new or modified files so that their changes can be included in the next commit. It moves changes from the working directory to the staging area; it does not create a commit by itself.

9. git status
git diff
git log --oneline
Rename-item gitnotes.md git-notes.md

Purpose: To check the variations between last commit or push with the present changes, is it committed or not.
git log --oneline is used to check the history of all the commits made in a repo.
Rename-item is used to rename a file already saved in a repo, doesn't change the contents but only the file name.

9. git branch -m brach.name
*Example: git branch -m main*
Purpose: This is to switch the current working branch.

10. git commit -m "message"
Purpose: This is used to save the changes made to the files and save it locally. The files added by the git commit will only be saved by the commit.

11. git rollback
Purpose: This command is used to revert back the changes made by the git commit command.

12. git push -u origin main
Purpose: This command is used to push the commited files to the cloud or the github repo.

13. git remote -v
Purpose: Manages connections to remote repositories, such as repositories hosted on GitHub. It lets you see which online repository your local project is connected to.

14. git pull 
Purpose: Downloads changes from a remote repository and integrates them into your current local branch. By default, Git usually performs a fetch followed by a merge, although configuration can make it use rebase instead.

15. git fetch
Purpose: Downloads new commits and branch information from a remote repository without automatically merging those changes into your current branch.

16. git branch -m feature-branch.name
Purpose: To create a feature branch and make changes to it for better organisation of the code.