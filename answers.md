Answer One:
dhawley@pu1:~/2400/git-lab$ touch README.md, answers.md
dhawley@pu1:~/2400/git-lab$ git --version
git version 2.17.1

Answer Two:
dhawley@pu1:~/2400/git-lab$ git config --global user.name "Frank Hawley"
dhawley@pu1:~/2400/git-lab$ git config --global user.email "dh438016@ohio.edu"
dhawley@pu1:~/2400/git-lab$ git config --list
user.name=Frank Hawley
user.email=dh438016@ohio.edu


Answer Three:
When Typing <git --help> you will be shown a screen that includes all common commands used by git.
This will include usage at the very top, then a categorized list of all common commands, with a brief line on what they do.
Finally at the end it will describe how to get help with subcommands. Typing <git --help> is sort of like a small little cheat sheet into what you use git for.

Answer Four:
dhawley@pu1:~/2400/git-lab$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer Five:
dhawley@pu1:~/2400/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

dhawley@pu1:~/2400/git-lab$

Question Six:
dhawley@pu1:~/2400/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

dhawley@pu1:~/2400/git-lab$ 

Question Seven:
dhawley@pu1:~/2400/git-lab$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
dhawley@pu1:~/2400/git-lab$ 

Question Eight:
dhawley@pu1:~/2400/git-lab$ git log
commit 2d37bb9566ec2af41d7fbd29a924f7ad589cacb7 (HEAD -> master)
Author: Frank Hawley <dh438016@ohio.edu>
Date:   Fri Sep 8 14:12:39 2023 -0400

    Initial Commit
dhawley@pu1:~/2400/git-lab$ 

Question Nine:
dhawley@pu1:~/2400/git-lab$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
dhawley@pu1:~/2400/git-lab$ 

Question Ten:
 
