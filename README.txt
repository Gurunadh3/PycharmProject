Hi everyone welcome home!

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git init
Reinitialized existing Git repository in /Users/gurunadhpamarthi/PycharmProjects/pythonProject1/.git/
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git remote add origin https://github.com/Gurunadh3/PycharmProject.git
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .idea/
        execute.py
        main.py

nothing added to commit but untracked files present (use "git add" to track)
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git add .
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .idea/.gitignore
        new file:   .idea/inspectionProfiles/profiles_settings.xml
        new file:   .idea/misc.xml
        new file:   .idea/modules.xml
        new file:   .idea/pythonProject1.iml
        new file:   .idea/vcs.xml
        new file:   execute.py
        new file:   main.py

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git commit -m "Initial Commit"
[main (root-commit) a81e1fe] Initial Commit
 8 files changed, 47 insertions(+)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/inspectionProfiles/profiles_settings.xml
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/pythonProject1.iml
 create mode 100644 .idea/vcs.xml
 create mode 100644 execute.py
 create mode 100644 main.py
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Gurunadh3/PycharmProject.git'
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push -u origin main
Username for 'https://github.com': Gurunadh3
Password for 'https://Gurunadh3@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Gurunadh3/PycharmProject.git/'
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push -u origin main
Username for 'https://github.com': Gurunadh3
Password for 'https://Gurunadh3@github.com':
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (12/12), 1.60 KiB | 1.60 MiB/s, done.
Total 12 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Gurunadh3/PycharmProject.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.txt

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git log
commit a81e1fe063cb377354de02edbc9f4aa68ddad801 (HEAD -> main, origin/main)
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:30:37 2024 -0500

    Initial Commit
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.txt

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git add README.txt
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.txt

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git commit -m "Secondary Commit"
[main 60f48e5] Secondary Commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 385 bytes | 385.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Gurunadh3/PycharmProject.git
   a81e1fe..60f48e5  main -> main
branch 'main' set up to track 'origin/main'.
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git checkout -b varun
Switched to a new branch 'varun'
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git log
commit 60f48e5db8cd949c8003e8bce5809d59f0f7398e (HEAD -> varun, origin/main, main)
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:44:32 2024 -0500

    Secondary Commit

commit a81e1fe063cb377354de02edbc9f4aa68ddad801
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:30:37 2024 -0500

    Initial Commit
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push -u origin varun
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'varun' on GitHub by visiting:
remote:      https://github.com/Gurunadh3/PycharmProject/pull/new/varun
remote:
To https://github.com/Gurunadh3/PycharmProject.git
 * [new branch]      varun -> varun
branch 'varun' set up to track 'origin/varun'.
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git log
commit 60f48e5db8cd949c8003e8bce5809d59f0f7398e (HEAD -> varun, origin/varun, origin/main, main)
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:44:32 2024 -0500

    Secondary Commit

commit a81e1fe063cb377354de02edbc9f4aa68ddad801
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:30:37 2024 -0500

    Initial Commit
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is up to date with 'origin/varun'.

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git log
commit 60f48e5db8cd949c8003e8bce5809d59f0f7398e (HEAD -> varun, origin/varun, origin/main, main)
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:44:32 2024 -0500

    Secondary Commit

commit a81e1fe063cb377354de02edbc9f4aa68ddad801
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:30:37 2024 -0500

    Initial Commit
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is up to date with 'origin/varun'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   execute.py

no changes added to commit (use "git add" and/or "git commit -a")
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git add .
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is up to date with 'origin/varun'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   execute.py

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git commit -m "finalized changes in varun branch"
[varun 630d4c2] finalized changes in varun branch
 1 file changed, 3 insertions(+), 1 deletion(-)
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is ahead of 'origin/varun' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git log
commit 630d4c25875a11039cc0321f07dd0e2648571616 (HEAD -> varun)
commit 630d4c25875a11039cc0321f07dd0e2648571616 (HEAD -> varun)
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 13:18:19 2024 -0500

    finalized changes in varun branch

commit 60f48e5db8cd949c8003e8bce5809d59f0f7398e (origin/varun, origin/main, main)
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
Date:   Wed Jun 12 12:44:32 2024 -0500

    Secondary Commit

commit a81e1fe063cb377354de02edbc9f4aa68ddad801
Author: “Gurunadh3” <“gurunadhprasad3@gmail.com”>
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is ahead of 'origin/varun' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git merge varun
Updating 60f48e5..630d4c2
Fast-forward
 execute.py | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Gurunadh3/PycharmProject.git
   60f48e5..630d4c2  main -> main
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git checkout varun
Switched to branch 'varun'
Your branch is ahead of 'origin/varun' by 1 commit.
  (use "git push" to publish your local commits)
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is ahead of 'origin/varun' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   sai.ipynb

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   sai.ipynb

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git add .
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is ahead of 'origin/varun' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   sai.ipynb

(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git commit -m "added new ipynb file"
[varun 6fdd19a] added new ipynb file
 1 file changed, 35 insertions(+)
 create mode 100644 sai.ipynb
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch varun
Your branch is ahead of 'origin/varun' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git merge varun
Updating 630d4c2..6fdd19a
Fast-forward
 sai.ipynb | 35 +++++++++++++++++++++++++++++++++++
 1 file changed, 35 insertions(+)
 create mode 100644 sai.ipynb
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 586 bytes | 586.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Gurunadh3/PycharmProject.git
   630d4c2..6fdd19a  main -> main
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
(venv) (base) gurunadhpamarthi@Gurunadhs-MacBook-Air pythonProject1 %

