1) --global = applies everywhere
    No --global = applies only to the current repo

2) The .git directory appeared in ls -a but not in normal ls. It contains Git's internal files and folders that store the repository's history, configuration, references, and other information needed for Git to track the project.

3) Git is offering 5 files/folders to track. .DS_Store looks like something I did not create intentionally because it is a macOS system file.

4) .venv/ and .DS_Store disappeared from the git status list because they are now being ignored by .gitignore.

5) .gitignore should be committed. It tells Git which files/folders to ignore, so other people working on the repository get the same rules. It should not be ignored itself.

6) README.md is now staged and ready to be included in the next commit.

7) Git printed [main (root-commit) d04caa9] lab work so far and reported 6 files changed, with 295 insertions.

8) The first seven characters, d04caa9, are called the short commit hash (or abbreviated commit ID). They are used to identify and reference that specific commit.

9)