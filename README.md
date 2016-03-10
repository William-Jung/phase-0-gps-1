# phase-0-gps-1
desktop :> cd phase-0-gps-1
change directory into repository

phase-0-gps-1 [master] :> ls
LICENSE   README.md
phase-0-gps-1 [master] :> git checkout -b gps-1-feature
created a new branch for our feature

Switched to a new branch 'gps-1-feature'
phase-0-gps-1 [gps-1-feature] :> touch awesome_page.md
created a new markdown page

phase-0-gps-1 [gps-1-feature] :> ls
LICENSE         README.md       awesome_page.md
phase-0-gps-1 [gps-1-feature] :> git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.
phase-0-gps-1 [master] :> git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	awesome_page.md

nothing added to commit but untracked files present (use "git add" to track)
phase-0-gps-1 [master] :> git push origin master
pushed everything from our local repository back to GitHub

Username for 'https://github.com': William-Jung
Password for 'https://William-Jung@github.com':
Everything up-to-date
phase-0-gps-1 [master] :> git checkout gps-1-feature
Switched to branch 'gps-1-feature'
phase-0-gps-1 [gps-1-feature] :> git status
On branch gps-1-feature
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	awesome_page.md

nothing added to commit but untracked files present (use "git add" to track)
phase-0-gps-1 [gps-1-feature] :> git branch -m gps-1-feature add-command-log
changed the name of the branch from gps-1-feature to add-command-log

phase-0-gps-1 [add-command-log] :> ls
LICENSE         README.md       awesome_page.md
phase-0-gps-1 [add-command-log] :> cd readme.md
-bash: cd: readme.md: Not a directory
phase-0-gps-1 [add-command-log] :> subl README.md
opened up markdown page in Sublime

phase-0-gps-1 [add-command-log] :>