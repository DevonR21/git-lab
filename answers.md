1. git version 2.17.1

2. user.name=Devon Risner
user.email=dr692920@ohio.edu

3. a bunch of information and help is given about the git add command

4. README.md and answers.md are both untracked files in the git-lab directory

5. It now shows README.md as a tracked file to be committed while answers.md is still untracked

6. now both files are green and to be committed

7. "On branch master, nothing to commit, working tree clean" meaning all files added have been committed

8. drisner@odd17:~/git-lab$ git commit -m "Initial Commit"
[master (root-commit) cc49721] Initial Commit
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md
drisner@odd17:~/git-lab$ git status
On branch master
nothing to commit, working tree clean
drisner@odd17:~/git-lab$ git log
commit cc497212c387e410e86859b9178bba43f9b92284 (HEAD -> master)
Author: Devon Risner <dr692920@ohio.edu>
Date:   Fri Sep 9 16:31:20 2022 -0400

    Initial Commit

9. The branch is up to date with 'origin/main' 

10.  There are no local changes made

11. An error was thrown  saying there has been changes made

12. now the changes made on github are shown locally

13. . .. .git .gitignore README.md

