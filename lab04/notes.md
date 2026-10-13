1) --global = applies everywhere
    No --global = applies only to the current repo

2) The .git directory appeared in ls -a but not in normal ls. It contains Git's internal files and folders that store the repository's history, configuration, references, and other information needed for Git to track the project.

3) Git is offering 5 files/folders to track. .DS_Store looks like something I did not create intentionally because it is a macOS system file.

4) .venv/ and .DS_Store disappeared from the git status list because they are now being ignored by .gitignore.

5) .gitignore should be committed. It tells Git which files/folders to ignore, so other people working on the repository get the same rules. It should not be ignored itself.

6) README.md is now staged and ready to be included in the next commit.

7) Git printed [main (root-commit) d04caa9] lab work so far and reported 6 files changed, with 295 insertions.

8) The first seven characters, d04caa9, are called the short commit hash (or abbreviated commit ID). They are used to identify and reference that specific commit.

9) The four steps of the Git edit-stage-commit loop are:

Edit: Make changes to your files.
Stage: Use git add to select the changes for the next commit.
Commit: Use git commit to save those staged changes as a snapshot.
Repeat: Make more changes and repeat the cycle.

10) README.md is given a special name and placed at the root of the repository because it serves as the main introduction/documentation for the project. GitHub automatically displays the root README.md on the repository's main page, so visitors can quickly understand the project and its contents.

11) gh auth login authenticates the GitHub CLI with your GitHub account and stores your credentials/token securely. This allows Git/GitHub CLI to authenticate you when you push, so you don't have to enter your GitHub password each time.

12) The README.md file is showing on the front page because GitHub automatically renders the repository's root README.md as the main documentation/introduction for the repository.

13) No. Pushing did not change my local Git history. git log --oneline still shows the same three commits; pushing only uploaded those commits to the remote GitHub repository.

14) A private repository exists on GitHub, but only people who have been given permission can see or access it. A repository that doesn't exist on GitHub at all cannot be accessed or viewed there because it hasn't been created or uploaded to GitHub.

