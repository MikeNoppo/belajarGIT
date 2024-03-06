# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-git

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ ^C

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git add Tugas-git
fatal: pathspec 'Tugas-git' did not match any files

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ nano Tugas-git.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-git.txt


ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git commit -m "Tugas-git"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ardia@PMDMINUT23.(none)')

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git config --global user.name "MikelNoppo"

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git config --global user.email "mikelnoppo03@gmail.com"

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ ^C

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git commit -m "Tugas-git"
[Tugas-git 9fc6e70] Tugas-git
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-git.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git log
commit 9fc6e70cc3709cde723b9581dab3cea444d6d221 (HEAD -> Tugas-git)
Author: MikelNoppo <mikelnoppo03@gmail.com>
Date:   Wed Mar 6 19:59:59 2024 +0800

    Tugas-git

commit e0b792f663c968dad8ee0f0b285e0f87b15be9c0 (origin/main, origin/HEAD, main)
Author: MikeNoppo <115890399+MikeNoppo@users.noreply.github.com>
Date:   Wed Mar 6 14:06:30 2024 +0800

    isi file README.md

commit 1050ff16d4227660aca6ac6ce71b249b2c266f89
Author: MikeNoppo <115890399+MikeNoppo@users.noreply.github.com>
Date:   Wed Mar 6 14:04:25 2024 +0800

    Initial commit

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git cheackout main
git: 'cheackout' is not a git command. See 'git --help'.

The most similar command is
        checkout

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-git
Updating e0b792f..9fc6e70
Fast-forward
 Tugas-git.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-git.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MikeNoppo/belajarGIT
   e0b792f..9fc6e70  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-html

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-html)
$ nano Tugas-html.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-html)
$ git commit -m "Tugas-html"
[Tugas-html d83af3f] Tugas-html
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-html.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-Html
Updating 9fc6e70..d83af3f
Fast-forward
 Tugas-html.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-html.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MikeNoppo/belajarGIT
   9fc6e70..d83af3f  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-css

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-css)
$ nano Tugas-css.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-css)
$ git commit -m "tugas-css"
[Tugas-css ee626d1] tugas-css
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-css.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-css)
$ git push
fatal: The current branch Tugas-css has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Tugas-css

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-css
Updating d83af3f..ee626d1
Fast-forward
 Tugas-css.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-css.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 359 bytes | 359.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MikeNoppo/belajarGIT
   d83af3f..ee626d1  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-js

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-js)
$ nano Tugas-js.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-js)
$ git commit -m "tugas-js"
[Tugas-js 9595fb6] tugas-js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-js
Updating ee626d1..9595fb6
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 285 bytes | 285.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MikeNoppo/belajarGIT
   ee626d1..9595fb6  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch midProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch -d midProject
Deleted branch midProject (was 9595fb6).

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-midProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ nano Tugas-midProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ git add^C

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ git add .

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ git commit -m "midProject"
[Tugas-midProject b766c8a] midProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-midProject
Updating 9595fb6..b766c8a
Fast-forward
 Tugas-midProject | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MikeNoppo/belajarGIT
   9595fb6..b766c8a  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-php

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-php)
$ touch Tugas-php

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-php)
$ nano Tugas-php.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-php)
$ git add .

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-php)
$ git commit -m "tugas-php"
[Tugas-php 1f08cac] tugas-php
 2 files changed, 2 insertions(+)
 rename Tugas-midProject => Tugas-midProject.txt (100%)
 create mode 100644 Tugas-php.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-php
Updating b766c8a..1f08cac
Fast-forward
 Tugas-midProject => Tugas-midProject.txt | 0
 Tugas-php.txt                            | 2 ++
 2 files changed, 2 insertions(+)
 rename Tugas-midProject => Tugas-midProject.txt (100%)
 create mode 100644 Tugas-php.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MikeNoppo/belajarGIT
   b766c8a..1f08cac  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git branch Tugas-finalProject

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-finalProject)
$ nano Tugas-finalProject.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-finalProject)
$ git add .

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-finalProject)
$ git commit -m "finalProject"
[Tugas-finalProject 11a06df] finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 1f08cac..11a06df
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 289 bytes | 289.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MikeNoppo/belajarGIT
   1f08cac..11a06df  main -> main

ardia@PMDMINUT23 MINGW64 /c/Michael/Kampus/WebDev/belajarGIT (main)
$

