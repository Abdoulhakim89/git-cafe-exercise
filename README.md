# git-cafe-exercise
## Bundle 5
### Exercise 1
```
User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1
$ git clone https://github.com/Abdoulhakim89/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 2.69 MiB/s, done.
Resolving deltas: 100% (5/5), done.
Updating files: 100% (106/106), done.

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1
$ cd git-cafe-exercise/

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (main)
$ git commit -a -m "Changes from Place to Restaurant on index.html file"
[main a14d480] Changes from Place to Restaurant on index.html file
 1 file changed, 1 insertion(+), 1 deletion(-)

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 116.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Abdoulhakim89/git-cafe-exercise.git
   d1d3f9c..a14d480  main -> main
```
### Bundle 6
### Exercise 1
```
User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (main)
$ git checkout -b Exercise1
Switched to a new branch 'Exercise1'

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (Exercise1)
$ git checkout -b ft/menu
Switched to a new branch 'ft/menu'

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ touch menu.html

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ git commit -a -m "Created a menu page and added some changes"
[ft/menu 545edf7] Created a menu page and added some changes
 1 file changed, 39 insertions(+)

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ git push --set-upstream origin ft/menu
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 877 bytes | 18.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/Abdoulhakim89/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/Abdoulhakim89/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ git add .

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ git commit -m "menu page"
[ft/menu e33ed6f] menu page
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html

User@ABDUL-HAKIM-MUHOZI MINGW64 ~/OneDrive/Desktop/Git_Exercises 1/git-cafe-exercise (ft/menu)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 438 bytes | 12.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Abdoulhakim89/git-cafe-exercise.git
   545edf7..e33ed6f  ft/menu -> ft/menu
```