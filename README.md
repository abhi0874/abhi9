# abhi9
9th

C:\Users\admin>cd C:\ai59\gitlab\expe7

C:\ai59\gitlab\expe7>ggh.txt
'ggh.txt' is not recognized as an internal or external command,
operable program or batch file.

C:\ai59\gitlab\expe7>gg.txt

C:\ai59\gitlab\expe7>git init
Initialized empty Git repository in C:/ai59/gitlab/expe7/.git/

C:\ai59\gitlab\expe7>gg.txt

C:\ai59\gitlab\expe7>git init
Reinitialized existing Git repository in C:/ai59/gitlab/expe7/.git/

C:\ai59\gitlab\expe7>git add gg.txt

C:\ai59\gitlab\expe7>git commit -m gg.txt
[master (root-commit) 5ab4f15] gg.txt
 1 file changed, 2 insertions(+)
 create mode 100644 gg.txt

C:\ai59\gitlab\expe7>git commit -m "add"
On branch master
nothing to commit, working tree clean

C:\ai59\gitlab\expe7>gg.txt

C:\ai59\gitlab\expe7>git add gg.txt

C:\ai59\gitlab\expe7>git commit -m "add functionality"
[master 67a0b35] add functionality
 1 file changed, 2 insertions(+)

C:\ai59\gitlab\expe7>git add gg.txt

C:\ai59\gitlab\expe7>git commit -m "sub functionality"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   gg.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\ai59\gitlab\expe7>git add gg.txt

C:\ai59\gitlab\expe7>git commit -m "sub functionality"
[master 997eb52] sub functionality
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\ai59\gitlab\expe7>git tag v1.0

C:\ai59\gitlab\expe7>git log
commit 997eb52061da2a76dc74185ff5a75541a24a8f12 (HEAD -> master, tag: v1.0)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:42:07 2024 +0530

    sub functionality

commit 67a0b35d5f0c77f4cccb308850115fdeb5ae405b
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:40:53 2024 +0530

    add functionality

commit 5ab4f154ca0535853b549c5ce6e5f89bd923e42c
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:39:13 2024 +0530

    gg.txt

C:\ai59\gitlab\expe7>git add gg.txt

C:\ai59\gitlab\expe7>git commit -m "mul functionality"
[master 8c216a6] mul functionality
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\ai59\gitlab\expe7>git add gg.txt

C:\ai59\gitlab\expe7>git commit -m "div functionality"
[master f76691f] div functionality
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\ai59\gitlab\expe7>git tag v2.0

C:\ai59\gitlab\expe7>git log
commit f76691f381c1774754121b2602ba71667aab23f9 (HEAD -> master, tag: v2.0)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:44:20 2024 +0530

    div functionality

commit 8c216a6dbd3e432eaa667915bd74ba2f97df6e48
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:43:50 2024 +0530

    mul functionality

commit 997eb52061da2a76dc74185ff5a75541a24a8f12 (tag: v1.0)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:42:07 2024 +0530

    sub functionality

commit 67a0b35d5f0c77f4cccb308850115fdeb5ae405b
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:40:53 2024 +0530

    add functionality

commit 5ab4f154ca0535853b549c5ce6e5f89bd923e42c
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:39:13 2024 +0530

    gg.txt

C:\ai59\gitlab\expe7>git tag -l
v1.0
v2.0

C:\ai59\gitlab\expe7>git tag -d v1.0
Deleted tag 'v1.0' (was 997eb52)

C:\ai59\gitlab\expe7>git tag -d v2.0
Deleted tag 'v2.0' (was f76691f)

C:\ai59\gitlab\expe7>git tag v1.0

C:\ai59\gitlab\expe7>git tag v2.0

C:\ai59\gitlab\expe7>git log
commit f76691f381c1774754121b2602ba71667aab23f9 (HEAD -> master, tag: v2.0, tag: v1.0)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:44:20 2024 +0530

    div functionality

commit 8c216a6dbd3e432eaa667915bd74ba2f97df6e48
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:43:50 2024 +0530

    mul functionality

commit 997eb52061da2a76dc74185ff5a75541a24a8f12
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:42:07 2024 +0530

    sub functionality

commit 67a0b35d5f0c77f4cccb308850115fdeb5ae405b
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:40:53 2024 +0530

    add functionality

commit 5ab4f154ca0535853b549c5ce6e5f89bd923e42c
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:39:13 2024 +0530

    gg.txt

C:\ai59\gitlab\expe7>git tag v1.0 997eb52061da2a76dc74185ff5a75541a24a8f12
fatal: tag 'v1.0' already exists

C:\ai59\gitlab\expe7>git tag v1.0
fatal: tag 'v1.0' already exists

C:\ai59\gitlab\expe7>git show f76691f381c1774754121b2602ba71667aab23f9
commit f76691f381c1774754121b2602ba71667aab23f9 (HEAD -> master, tag: v2.0, tag: v1.0)
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:44:20 2024 +0530

    div functionality

diff --git a/gg.txt b/gg.txt
index d998c2c..be8475d 100644
--- a/gg.txt
+++ b/gg.txt
@@ -3,4 +3,5 @@ hj

 kl
 pl
-jl
\ No newline at end of file
+jl
+kj
\ No newline at end of file

C:\ai59\gitlab\expe7>git log -n 997eb52061da2a76dc74185ff5a75541a24a8f12
fatal: '997eb52061da2a76dc74185ff5a75541a24a8f12': not an integer

C:\ai59\gitlab\expe7>git log -n 2 997eb52061da2a76dc74185ff5a75541a24a8f12
commit 997eb52061da2a76dc74185ff5a75541a24a8f12
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:42:07 2024 +0530

    sub functionality

commit 67a0b35d5f0c77f4cccb308850115fdeb5ae405b
Author: suraj-6 <suraj.204214@gmail.com>
Date:   Sat Mar 9 07:40:53 2024 +0530

    add functionality

C:\ai59\gitlab\expe7>
