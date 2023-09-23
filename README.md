This is the README for the root of the repository
Github cloning
root@e0392e09302c:/# cd alx-pre_course
root@e0392e09302c:/alx-pre_course# cd 0x01-git
root@e0392e09302c:/alx-pre_course/0x01-git# touch bash/98
root@e0392e09302c:/alx-pre_course/0x01-git# rm bash/98
root@e0392e09302c:/alx-pre_course/0x01-git# git checkout -b update_script
fatal: A branch named 'update_script' already exists.
root@e0392e09302c:/alx-pre_course/0x01-git# touch bash/98
root@e0392e09302c:/alx-pre_course/0x01-git# sed -i 's/echo "ALX"/echo "ALX School"/' bash/alx
root@e0392e09302c:/alx-pre_course/0x01-git# sed -i 's/echo "School"/echo "The school is open!"/' bash/school
root@e0392e09302c:/alx-pre_course/0x01-git# git add .
root@e0392e09302c:/alx-pre_course/0x01-git# git commit -m "My personal work"
[update_script 7df831a] My personal work
 3 files changed, 2 insertions(+), 2 deletions(-)
 create mode 100644 0x01-git/bash/98
root@e0392e09302c:/alx-pre_course/0x01-git# git chckout main
git: 'chckout' is not a git command. See 'git --help'.

The most similar command is
        checkout
root@e0392e09302c:/alx-pre_course/0x01-git# git checkout main
error: pathspec 'main' did not match any file(s) known to git
root@e0392e09302c:/alx-pre_course/0x01-git# git checkout main
error: pathspec 'main' did not match any file(s) known to git
root@e0392e09302c:/alx-pre_course/0x01-git# git branch -a
  master
* update_script
  remotes/origin/master
root@e0392e09302c:/alx-pre_course/0x01-git# git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
root@e0392e09302c:/alx-pre_course/0x01-git# sed -i 's/echo "ALX"/echo "ALX School is so cool!"/' bash/alx
root@e0392e09302c:/alx-pre_course/0x01-git# rm -rf js
root@e0392e09302c:/alx-pre_course/0x01-git# git add .
root@e0392e09302c:/alx-pre_course/0x01-git# git commit -m "Hot fix"
[master e05f7ee] Hot fix
 3 files changed, 1 insertion(+), 1 deletion(-)
 delete mode 100644 0x01-git/js/index.js
 delete mode 100644 0x01-git/js/main.js
root@e0392e09302c:/alx-pre_course/0x01-git# git push origin update_script
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 592 bytes | 592.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'update_script' on GitHub by visiting:
remote:      https://github.com/AyiembaPearl/alx-pre_course/pull/new/update_script
remote: 
To https://github.com/AyiembaPearl/alx-pre_course.git
 * [new branch]      update_script -> update_script
root@e0392e09302c:/alx-pre_course/0x01-git# git push origin master
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 496 bytes | 496.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/AyiembaPearl/alx-pre_course.git
   28a96d2..e05f7ee  master -> master
root@e0392e09302c:/alx-pre_course/0x01-git# 
