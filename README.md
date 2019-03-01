# urban-memory

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .mxproject
        Drivers/
        Inc/
        MDK-ARM/
        Middlewares/
        Src/
        chassis.ioc
        gitbak/
        infantry doc.docx
        infantryV2.1-12-22-release.hex

nothing added to commit but untracked files present (use "git add" to track)

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git add ^V^V
fatal: pathspec '?^V' did not match any files

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git add ^V
fatal: pathspec '^V' did not match any files

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git add ^V
fatal: pathspec '^V' did not match any files

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git add infantry doc.docx
fatal: pathspec 'infantry' did not match any files

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git add read.md

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   read.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .mxproject
        Drivers/
        Inc/
        MDK-ARM/
        Middlewares/
        Src/
        chassis.ioc
        gitbak/
        infantry doc.docx
        infantryV2.1-12-22-release.hex


dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git commit -m 'history'
[master 2cb4b6f] history
 1 file changed, 1 insertion(+)
 create mode 100644 read.md

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .mxproject
        Drivers/
        Inc/
        MDK-ARM/
        Middlewares/
        Src/
        chassis.ioc
        gitbak/
        infantry doc.docx
        infantryV2.1-12-22-release.hex

nothing added to commit but untracked files present (use "git add" to track)

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git remote add origin https://github.com/GithubMingEnter/urban-memory.git

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git push -u origin mater
error: src refspec mater does not match any.
error: failed to push some refs to 'https://github.com/GithubMingEnter/urban-memory.git'

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ touch rr

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git add rr

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git commit -m 'dkdk'
[master 034aa74] dkdk
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 rr

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$ git push origin master
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (9/9), 454.12 KiB | 9.87 MiB/s, done.
Total 9 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/GithubMingEnter/urban-memory.git
 * [new branch]      master -> master

dell@DESKTOP-L150TQ0 MINGW64 /e/大创，RM,数模/RM/2222/无跟随2.0/哈理工初始版本——ROS射击版本3_自己车车 (master)
$
