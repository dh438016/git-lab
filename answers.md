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
dhawley@pu1:~/2400/git-lab$ vi README.md

Github Username: dh438016
Full Name: Frank Hawley

Email: dh438016@ohio.edu

To the Teaching Assisstant,

This message was updated in a command line editor within pu1.cs.ohio.edu 

**
As you can see the changed were not reflected in the local git. since we are missing a line after pu1.cs.ohio.edu

Question Eleven:
To https://github.com/dh438016/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/dh438016/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The push did not go through because the online version contains information not found in the local version.

Question Twelve:
dhawley@pu1:~/2400/git-lab$ vi README.md

Github Username: dh438016
Full Name: Frank Hawley

Email: dh438016@ohio.edu

To the Teaching Assisstant,

This message was updated in a command line editor within pu1.cs.ohio.edu


CS 2400 Lab Section 104

Yes you can see the changes were made as the Class and lab section data is present now.

Question Thirteen:
dhawley@pu1:~/2400/git-lab-2$ ls -al
total 20
drwxr-xr-x  3 dhawley students 4096 Sep  8 14:44 .
drwxr-xr-x 18 dhawley students 4096 Sep  8 14:44 ..
drwxr-xr-x  8 dhawley students 4096 Sep  8 14:44 .git
-rw-r--r--  1 dhawley students  270 Sep  8 14:44 .gitignore
-rw-r--r--  1 dhawley students   11 Sep  8 14:44 README.md
dhawley@pu1:~/2400/git-lab-2$ 
