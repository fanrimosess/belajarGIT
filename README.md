# belajarGIT
Daftar tugas / branch

Tugas-git
Tugas-html
Tugas-css
Tugas-js
Tugas-midProject
Tugas-php
Tugas-finalProject

Daftar perintah GiT
User@DESKTOP-4QOMN34 MINGW64 ~
$ cd PemroWeb

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb
$ cd tugas

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas
$ git clone https://github.com/fanrimosess/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas
$ cd belajarGIT

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-git

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'User@DESKTOP-4QOMN34.(none)')

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git config --global user.email "fandrymoses
> @gmail.com"

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git config --global user.name "fanrimosess"

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 4dce390] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-git.txt
Please commit your changes or stash them before you switch branches.
Aborting

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git db6d1a1] Menambahkan file Tugas-git.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git merge Tugas-git
Updating 16ae2c4..db6d1a1
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 592 bytes | 592.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/fanrimosess/belajarGIT.git
   16ae2c4..db6d1a1  main -> main

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-html

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html ab98786] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 8c07749] Menambahkan file Tugas-html.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git merge Tugas-html
Updating db6d1a1..8c07749
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 552 bytes | 552.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/fanrimosess/belajarGIT.git
   db6d1a1..8c07749  main -> main

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-css

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css bb5ea8b] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css e8f9a0c] Menambahkan file Tugas-css.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-css)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git merge Tugas-css
Updating 8c07749..e8f9a0c
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 584 bytes | 584.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/fanrimosess/belajarGIT.git
   8c07749..e8f9a0c  main -> main

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-js

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js a96948f] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
On branch Tugas-js
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-js.txt

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 829ca3b] Menambahkan file Tugas-js.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git merge Tugas-js
Updating e8f9a0c..829ca3b
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 515 bytes | 515.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/fanrimosess/belajarGIT.git
   e8f9a0c..829ca3b  main -> main

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-midProject

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 2226422] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 059eb49] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git merge Tugas-midProject
Updating 829ca3b..059eb49
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 542 bytes | 542.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/fanrimosess/belajarGIT.git
   829ca3b..059eb49  main -> main

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-php

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 0eef21f] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$  git commit -m "Menambahkan file Tugas-php.txt"
On branch Tugas-php
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-php.txt

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 2beb8f7] Menambahkan file Tugas-php.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git merge Tugas-php
Updating 059eb49..2beb8f7
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 517 bytes | 517.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/fanrimosess/belajarGIT.git
   059eb49..2beb8f7  main -> main

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git branch Tugas-finalProject

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 5d8072e] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-finalProject.txt
Please commit your changes or stash them before you switch branches.
Aborting

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$  git merge Tugas-finalProject
Already up to date.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-finalProject.txt
Please commit your changes or stash them before you switch branches.
Aborting

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 1724615] Menambahkan file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$  git merge Tugas-finalProject
Updating 2beb8f7..1724615
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

User@DESKTOP-4QOMN34 MINGW64 ~/PemroWeb/tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 544 bytes | 544.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/fanrimosess/belajarGIT.git
   2beb8f7..1724615  main -> main
