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
## bundle 2 
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
 ##bundle 3 
 ###Exercises 2
 didierd@Patrick-MacBook HTML % git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
didierd@Patrick-MacBook HTML % git add --all
didierd@Patrick-MacBook HTML % git commit -m "add faq pages"
[ft/faq-page 0fb2528] add faq pages
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
 create mode 100644 faq.html
didierd@Patrick-MacBook HTML % git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

didierd@Patrick-MacBook HTML % git push --set-upstream origin ft/faq-page
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 465 bytes | 465.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/mahorogit/Gym-Git-Exercises-Solutions.git
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/mahorogit/Gym-Git-Exercises-Solutions/pull/new/ft/faq-page
remote: 
To https://github.com/mahorogit/-Gym_prep_exercises.git
 * [new branch]      ft/faq-page -> ft/faq-page
Branch 'ft/faq-page' set up to track remote branch 'ft/faq-page' from 'origin'.
didierd@Patrick-MacBook HTML % git log
commit 0fb25287afb32211c4339d7e3a524c4b2b944c8d (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:15:44 2023 +0200

    add faq pages

commit 87205d5b12fa943e7928b7b2e31f62162650d741 (origin/ft/contact-page, ft/contact-page)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:08:51 2023 +0200

    add contact pages

commit c609a83458c50484f27dd388067aaadccf576b34
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 07:45:17 2023 +0200

    add team pages
didierd@Patrick-MacBook HTML % git revert c609a83458c50484f27dd388067aaadccf576b34
[ft/faq-page 4b20400] Revert "add team pages"
 Committer: Mahoro Patrick <didierd@Patrick-MacBook.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 11 deletions(-)
 delete mode 100644 team.html
didierd@Patrick-MacBook HTML % git push
Counting objects: 2, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 279 bytes | 279.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/mahorogit/Gym-Git-Exercises-Solutions.git
To https://github.com/mahorogit/-Gym_prep_exercises.git
   0fb2528..4b20400  ft/faq-page -> ft/faq-page
didierd@Patrick-MacBook HTML % git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
didierd@Patrick-MacBook HTML % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
didierd@Patrick-MacBook HTML % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
didierd@Patrick-MacBook HTML % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
didierd@Patrick-MacBook HTML % git add --all
didierd@Patrick-MacBook HTML % git commit -m "changing home page" 
[main 134f9da] changing home page
 Committer: Mahoro Patrick <didierd@Patrick-MacBook.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 3 insertions(+)
didierd@Patrick-MacBook HTML % git log
commit 134f9da8bf1f009073ae5442f0888a396939be4b (HEAD -> main)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:39:05 2023 +0200

    changing home page

commit 6cc6cf3cc8819dbe22129e7c023abe4e481ed0ee (origin/main)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Mon May 15 20:26:49 2023 +0200

    updated services changes

commit 8dd58265b53d93635a08c2d18ce17ac8ef7abcde
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Mon May 15 18:37:46 2023 +0200

    old services changes
didierd@Patrick-MacBook HTML % git checkout -b ft/home-page-redesign
fatal: A branch named 'ft/home-page-redesign' already exists.
didierd@Patrick-MacBook HTML % git status                           
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
didierd@Patrick-MacBook HTML % git log
commit 134f9da8bf1f009073ae5442f0888a396939be4b (HEAD -> main)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:39:05 2023 +0200

    changing home page

commit 6cc6cf3cc8819dbe22129e7c023abe4e481ed0ee (origin/main)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Mon May 15 20:26:49 2023 +0200

    updated services changes

commit 8dd58265b53d93635a08c2d18ce17ac8ef7abcde
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Mon May 15 18:37:46 2023 +0200

    old services changes
didierd@Patrick-MacBook HTML % git checkout ft/home-page-redesign 
Switched to branch 'ft/home-page-redesign'
didierd@Patrick-MacBook HTML % git rebase main
First, rewinding head to replay your work on top of it...
Applying: add team pages
Applying: add contact pages
Applying: add faq pages
Applying: Revert "add team pages"
didierd@Patrick-MacBook HTML % git status
On branch ft/home-page-redesign
nothing to commit, working tree clean
didierd@Patrick-MacBook HTML % git log
commit 888041557898d1d8472f1bd0c1d2c74b7244298d (HEAD -> ft/home-page-redesign)
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:21:44 2023 +0200

    Revert "add team pages"
    
    This reverts commit c609a83458c50484f27dd388067aaadccf576b34.

commit dbe3f5277222ed1bad50331ec916ed1a6d9c477e
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:15:44 2023 +0200

    add faq pages

commit 73b7b1bdd8036921bf86a5350ff88c1cc4cff1b2
Author: Mahoro Patrick <didierd@Patrick-MacBook.local>
Date:   Tue May 16 08:08:51 2023 +0200

didierd@Patrick-MacBook HTML % git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
didierd@Patrick-MacBook HTML % git add home.html
didierd@Patrick-MacBook HTML % git commit -m "add home page menu"   
[ft/home-page-redesign 5043e54] add home page menu
 Committer: Mahoro Patrick <didierd@Patrick-MacBook.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 5 insertions(+)
didierd@Patrick-MacBook HTML % git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

didierd@Patrick-MacBook HTML % git push --set-upstream origin ft/home-page-redesign
Counting objects: 17, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 1.77 KiB | 453.00 KiB/s, done.
Total 17 (delta 10), reused 0 (delta 0)
remote: Resolving deltas: 100% (10/10), completed with 2 local objects.
remote: This repository moved. Please use the new location:
remote:   https://github.com/mahorogit/Gym-Git-Exercises-Solutions.git
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/mahorogit/Gym-Git-Exercises-Solutions/pull/new/ft/home-page-redesign
remote: 
To https://github.com/mahorogit/-Gym_prep_exercises.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
Branch 'ft/home-page-redesign' set up to track remote branch 'ft/home-page-redesign' from 'origin'.
didierd@Patrick-MacBook HTML % git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
didierd@Patrick-MacBook HTML % >....                                                                                                                                    

didierd@Patrick-MacBook HTML % git push --set-upstream origin ft/home-page-redesign
Counting objects: 17, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 1.77 KiB | 453.00 KiB/s, done.
Total 17 (delta 10), reused 0 (delta 0)
remote: Resolving deltas: 100% (10/10), completed with 2 local objects.
remote: This repository moved. Please use the new location:
remote:   https://github.com/mahorogit/Gym-Git-Exercises-Solutions.git
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/mahorogit/Gym-Git-Exercises-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/mahorogit/-Gym_prep_exercises.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
Branch 'ft/home-page-redesign' set up to track remote branch 'ft/home-page-redesign' from 'origin'.   
zsh: parse error near `)'
