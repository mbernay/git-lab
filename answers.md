Answer 1: git version 2.17.1
Answer 2: user.name=Michael Bernay
user.email=mb246721@ohio.edu
Answer 3: It gives a list of common Git commands that are used in various situations and gives a brief description on what each command does.
Answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)
Answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md


Answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md


Answer 7: On branch master
nothing to commit, working tree clean

Answer 8: commit 7f66dcb1c50adf44217aef4177d1b838c96ce495 (HEAD -> master)
Author: Michael Bernay <mb246721@ohio.edu>
Date:   Fri Sep 9 16:36:02 2022 -0400

    Initial commit

Answer 9: Warning: Permanently added the ECDSA host key for IP address '140.82.114.4' to the list of known hosts.
Authenticated to github.com ([140.82.114.4]:22).
Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 276 bytes | 92.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
Transferred: sent 2648, received 2728 bytes, in 0.6 seconds
Bytes per second: sent 4809.5, received 4954.8
To github.com:mbernay/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

Answer 10: The changes made on the github website online are not reflected in the local file.

Answer 11: I get this error because the github version of the file is more recently updated than the local file so the local file must be updated to accomodate the changes on the github file:
Authenticated to github.com ([140.82.114.4]:22).
Transferred: sent 2204, received 2576 bytes, in 0.2 seconds
Bytes per second: sent 12075.2, received 14113.3
To github.com:mbernay/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'git@github.com:mbernay/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: The changes made online are now reflected in the local copy because we did a git pull to get the most recent version of the README.md

Answer 13: .  ..  .git  .gitignore  README.md
