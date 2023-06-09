/**
 *   @file: answers.md
 * @author: Dhruv Patel
 *   @date: 05/19/2023
 *  @brief: In this Hw1, we will learn about git and get to know more
            about the same.
           
 **/

// ANSWER 1: git version 2.39.2.windows.1

// ANSWER 2:
/**diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Dhruv Patel
user.email=dp856122@ohio.edu
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/Dhruvp1901/zipcode.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
**/


/** ANSWER 3: It took me into a chrome tab where it explained the git-add command and the other details
              related to it like its function and what does it do.
              So, the function of git-add command is to add file contents to the index.
**/


/** ANSWER 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)
**/


/** ANSWER 5: There is one tracked and one untracked file in our repo.
Output I got is:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
**/

/** ANSWER 6:Now, both the files are added to the repo by the git add command.
Output is:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
**/


/** ANSWER 7: After issuing the commit command, the output is:
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
**/


/** ANSWER 8: After issuing the git log command:
commit c284dd07c07df073d1cdc83a41e1ac79675142ce (HEAD -> master)
Author: Dhruv Patel <dp856122@ohio.edu>
Date:   Fri May 19 18:20:06 2023 -0400

    Initial commit
**/


/** ANSWER 9: After appyling the pushing existing repository from command line, I got the following
              output in my windows powershell:
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 20 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.45 KiB | 1.45 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Dhruvp1901/git-labCS2400.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
**/

// ANSWER 10: No, it is not changing in the local copy.


// ANSWER 11: No, it is still not showing in the local copy even after trying the push command again.


// ANSWER 12: Yes, now the changes are visible on my README.md file.

/** ANSWER 13: After appyling ls -a command, the output I got is:
Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible
matches include: -Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand
**/



