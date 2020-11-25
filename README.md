# pythonlearning

this  is my first git project



C:\anacondaTest>mkdir gitpojects

C:\anacondaTest>cd gitpojects

C:\anacondaTest\gitpojects>git clone https://github.com/ratnabhushan/pythonlearning.git
Cloning into 'pythonlearning'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

C:\anacondaTest\gitpojects>dir
 Volume in drive C has no label.
 Volume Serial Number is D68A-EDB9

 Directory of C:\anacondaTest\gitpojects

24-11-2020  19:16    <DIR>          .
24-11-2020  19:16    <DIR>          ..
24-11-2020  19:16    <DIR>          pythonlearning
               0 File(s)              0 bytes
               3 Dir(s)  138,822,270,976 bytes free

C:\anacondaTest\gitpojects>cd pythonlearning

C:\anacondaTest\gitpojects\pythonlearning>dir
 Volume in drive C has no label.
 Volume Serial Number is D68A-EDB9

 Directory of C:\anacondaTest\gitpojects\pythonlearning

24-11-2020  19:16    <DIR>          .
24-11-2020  19:16    <DIR>          ..
24-11-2020  19:16                16 README.md
               1 File(s)             16 bytes
               2 Dir(s)  138,823,397,376 bytes free

C:\anacondaTest\gitpojects\pythonlearning>cd ..

C:\anacondaTest\gitpojects>git status -s
fatal: not a git repository (or any of the parent directories): .git

C:\anacondaTest\gitpojects>cd pythonlearning

C:\anacondaTest\gitpojects\pythonlearning>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\anacondaTest\gitpojects\pythonlearning>git status -s
 M README.md

C:\anacondaTest\gitpojects\pythonlearning>git add *.md

C:\anacondaTest\gitpojects\pythonlearning>git status -s
M  README.md

C:\anacondaTest\gitpojects\pythonlearning>git commit -m "this is my first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'hp@DESKTOP-361Q0OF.(none)')

C:\anacondaTest\gitpojects\pythonlearning>git config --global user.email "rbj2801@gmail.com"

C:\anacondaTest\gitpojects\pythonlearning>git config --global user.name "ratnabhushan"

C:\anacondaTest\gitpojects\pythonlearning>git commit -m "this is my first commit"
[master 8c1bb13] this is my first commit
 1 file changed, 3 insertions(+), 1 deletion(-)

C:\anacondaTest\gitpojects\pythonlearning>git branch
* master

C:\anacondaTest\gitpojects\pythonlearning>git status -s

C:\anacondaTest\gitpojects\pythonlearning>git push origin master
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ratnabhushan/pythonlearning.git
   ac08fa5..8c1bb13  master -> master

C:\anacondaTest\gitpojects\pythonlearning>

