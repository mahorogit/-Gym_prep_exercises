# -Gym_prep_exercises
## Bundle 1
### exercises 1
didierd@Patrick-MacBook HTML % git init
Initialized empty Git repository in /Users/didierd/Desktop/HTML/.git/
didierd@Patrick-MacBook HTML % git add .                   
didierd@Patrick-MacBook HTML % git commit -m "first commit"
[master (root-commit) cbd2e70] first commit
 Committer: Mahoro Patrick <didierd@Patrick-MacBook.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 4 files changed, 105 insertions(+)
 create mode 100644 images/IMG_2198.jpeg
 create mode 100644 images/logo.jpeg
 create mode 100644 index.html
 create mode 100644 style.css
didierd@Patrick-MacBook HTML % git branch  
* master
didierd@Patrick-MacBook HTML % git branch -M main
didierd@Patrick-MacBook HTML % git branch        
* main
didierd@Patrick-MacBook HTML % git remote add origin https://github.com/mahorogit/-Gym_prep_exercises.git
didierd@Patrick-MacBook HTML % git push -u origin main
Counting objects: 7, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 994.29 KiB | 13.62 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0)
To https://github.com/mahorogit/-Gym_prep_exercises.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
didierd@Patrick-MacBook HTML % 
didierd@Patrick-MacBook HTML % git checkout
Your branch is up to date with 'origin/main'.
didierd@Patrick-MacBook HTML % git checkout -b dev
Switched to a new branch 'dev'
didierd@Patrick-MacBook HTML % git checkout -b test
Switched to a new branch 'test'
didierd@Patrick-MacBook HTML % git branch -b test
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged | --no-merged]
   or: git branch [<options>] [-l] [-f] <branch-name> [<start-point>]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track           set up tracking mode (see git-pull(1))
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      Unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display SHA-1s

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    --list                list branch names
    -l, --create-reflog   create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --format <format>     format to use for the output

didierd@Patrick-MacBook HTML % git branch -d test 
error: Cannot delete branch 'test' checked out at '/Users/didierd/Desktop/HTML'
didierd@Patrick-MacBook HTML % git branch                                                                
  dev
  main
* test
didierd@Patrick-MacBook HTML % git branch -d test
error: Cannot delete branch 'test' checked out at '/Users/didierd/Desktop/HTML'
didierd@Patrick-MacBook HTML % git branch -d test
error: Cannot delete branch 'test' checked out at '/Users/didierd/Desktop/HTML'
didierd@Patrick-MacBook HTML % git branch -d test  
error: Cannot delete branch 'test' checked out at '/Users/didierd/Desktop/HTML'
didierd@Patrick-MacBook HTML % git branch -d dev 
Deleted branch dev (was cbd2e70).
didierd@Patrick-MacBook HTML % git branch -b dev 
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged | --no-merged]
   or: git branch [<options>] [-l] [-f] <branch-name> [<start-point>]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track           set up tracking mode (see git-pull(1))
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      Unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display SHA-1s

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    --list                list branch names
    -l, --create-reflog   create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --format <format>     format to use for the output

didierd@Patrick-MacBook HTML % git checkout -b dev 
Switched to a new branch 'dev'
didierd@Patrick-MacBook HTML % git branch -b test  
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged | --no-merged]
   or: git branch [<options>] [-l] [-f] <branch-name> [<start-point>]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track           set up tracking mode (see git-pull(1))
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      Unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display SHA-1s

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    --list                list branch names
    -l, --create-reflog   create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --format <format>     format to use for the output

didierd@Patrick-MacBook HTML % git branch -d test 
Deleted branch test (was cbd2e70).
didierd@Patrick-MacBook HTML % 
 ### exercises 2
 didierd@Patrick-MacBook HTML % git stash list
didierd@Patrick-MacBook HTML % git add home.html
didierd@Patrick-MacBook HTML % git stash
Saved working directory and index state WIP on dev: cbd2e70 first commit
didierd@Patrick-MacBook HTML % git stash list
stash@{0}: WIP on dev: cbd2e70 first commit
didierd@Patrick-MacBook HTML % git add about.html
didierd@Patrick-MacBook HTML % git stash
Saved working directory and index state WIP on dev: cbd2e70 first commit
didierd@Patrick-MacBook HTML % git stash list
stash@{0}: WIP on dev: cbd2e70 first commit
stash@{1}: WIP on dev: cbd2e70 first commit
didierd@Patrick-MacBook HTML % git add team.html
didierd@Patrick-MacBook HTML % git stash
Saved working directory and index state WIP on dev: cbd2e70 first commit
didierd@Patrick-MacBook HTML % git stash list
stash@{0}: WIP on dev: cbd2e70 first commit
stash@{1}: WIP on dev: cbd2e70 first commit
stash@{2}: WIP on dev: cbd2e70 first commit
didierd@Patrick-MacBook HTML % git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   about.html

Dropped stash@{1} (6bf3b34ace3b3b4ed215e6f7b64d5c70cb299d4a)
didierd@Patrick-MacBook HTML % git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   about.html
        new file:   home.html

Dropped stash@{1} (b2443c124664d87582b6e6e270946993639642ff)
didierd@Patrick-MacBook HTML % git add .
didierd@Patrick-MacBook HTML % git commit -m  "stage commit" 
[dev d32b850] stage commit
 Committer: Mahoro Patrick <didierd@Patrick-MacBook.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 22 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
didierd@Patrick-MacBook HTML % git push origin dev
Counting objects: 11, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 994.75 KiB | 12.75 MiB/s, done.
Total 11 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
remote: This repository moved. Please use the new location:
remote:   https://github.com/mahorogit/Gym-Git-Exercises-Solutions.git
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/mahorogit/Gym-Git-Exercises-Solutions/pull/new/dev
remote: 
To https://github.com/mahorogit/-Gym_prep_exercises.git
 * [new branch]      dev -> dev
didierd@Patrick-MacBook HTML % git push -u  origin dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.
Everything up-to-date
didierd@Patrick-MacBook HTML % git push -u  origin main
To https://github.com/mahorogit/-Gym_prep_exercises.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/mahorogit/-Gym_prep_exercises.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
didierd@Patrick-MacBook HTML % git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
didierd@Patrick-MacBook HTML % git push origin dev  
Everything up-to-date
didierd@Patrick-MacBook HTML % git add .                    
didierd@Patrick-MacBook HTML % git commit -m  "stage commits"
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
didierd@Patrick-MacBook HTML % 
 didierd@Patrick-MacBook HTML % git reset --hard
HEAD is now at d32b850 stage commit
didierd@Patrick-MacBook HTML % 
##bundle 2 
 ### Exercises 1
 didierd@Patrick-MacBook HTML % git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
didierd@Patrick-MacBook HTML % git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        services.html

nothing added to commit but untracked files present (use "git add" to track)
didierd@Patrick-MacBook HTML % git add services.html
didierd@Patrick-MacBook HTML % git stash
Saved working directory and index state WIP on ft/bundle-2: d32b850 stage commit
didierd@Patrick-MacBook HTML % git stash pop
On branch ft/bundle-2
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   services.html

Dropped refs/stash@{0} (cd721c1a4b966e6bd687b6b31a76b08d4329eab3)
didierd@Patrick-MacBook HTML % git add service.html
fatal: pathspec 'service.html' did not match any files
didierd@Patrick-MacBook HTML % git add services.html
didierd@Patrick-MacBook HTML % git status
On branch ft/bundle-2
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   services.html

didierd@Patrick-MacBook HTML % git commit "create services page"
error: pathspec 'create services page' did not match any file(s) known to git.
didierd@Patrick-MacBook HTML % git commit -m "create services page"
[ft/bundle-2 2efa60a] create services page
 Committer: Mahoro Patrick <didierd@Patrick-MacBook.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 11 insertions(+)
 create mode 100644 services.html
didierd@Patrick-MacBook HTML % git status
On branch ft/bundle-2
nothing to commit, working tree clean
didierd@Patrick-MacBook HTML % git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

didierd@Patrick-MacBook HTML % <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git exercises | services</title>
</head>
<body>
    <h1>this is our services</h1>
</body>
</html>
zsh: parse error near `\n'
didierd@Patrick-MacBook HTML %  git push --set-upstream origin ft/bundle-2
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 477 bytes | 477.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/mahorogit/Gym-Git-Exercises-Solutions.git
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/mahorogit/Gym-Git-Exercises-Solutions/pull/new/ft/bundle-2
remote: 
To https://github.com/mahorogit/-Gym_prep_exercises.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
Branch 'ft/bundle-2' set up to track remote branch 'ft/bundle-2' from 'origin'.
