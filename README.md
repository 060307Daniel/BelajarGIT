Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

G@DESKTOP-PQ680AD MINGW64 ~
$ cd "C:\Users\G\Documents\KULIAH\Semester 4\web"

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web
$ git clone https://github.com/060307Daniel/BelajarGIT.git
Cloning into 'BelajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web
$ cd "C:\Users\G\Documents\KULIAH\Semester 4\web\BelajarGIT"

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-git

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-html

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-css

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-js

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-midProject

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-php

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ finalProject
bash: finalProject: command not found

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git branch Tugas-finalProject

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-git
Switched to branch 'Tugas-git'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-git)
$ git add Tugas-git.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-git)
$ git commit -m "Berhasil Pertama"
[Tugas-git 5929f6c] Berhasil Pertama
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-git)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-git
Updating 4b950e1..5929f6c
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/060307Daniel/BelajarGIT.git
   4b950e1..5929f6c  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-html
Switched to branch 'Tugas-html'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-html)
$ git commit -m "Berhasil Kedua"
[Tugas-html 4786aad] Berhasil Kedua
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-html)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-html
Merge made by the 'ort' strategy.
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 540 bytes | 540.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/060307Daniel/BelajarGIT.git
   5929f6c..64fa664  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-css
Switched to branch 'Tugas-css'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-css)
$ git add Tugas-css.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-css)
$ git commit -m "Berhasil Ketiga"
[Tugas-css 8461b83] Berhasil Ketiga
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-css)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 569 bytes | 569.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/060307Daniel/BelajarGIT.git
   64fa664..39007ba  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-js
Switched to branch 'Tugas-js'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-js)
$ git add Tugas-js.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-js)
$ git commit -m "Berhasil Keempat"
[Tugas-js 5d082a0] Berhasil Keempat
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-js)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 486 bytes | 486.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/060307Daniel/BelajarGIT.git
   39007ba..b62c5fb  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-midProject
Switched to branch 'Tugas-midProject'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-midProject)
$ git commit -m "Berhasil Kelima"
[Tugas-midProject 1072c68] Berhasil Kelima
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-midProject)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 518 bytes | 518.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/060307Daniel/BelajarGIT.git
   b62c5fb..c234d35  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-php
Switched to branch 'Tugas-php'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-php)
$ git add Tugas-php.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-php)
$ git commit -m "Berhasil Keenam"
[Tugas-php 16ef9ab] Berhasil Keenam
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-php)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 464 bytes | 464.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/060307Daniel/BelajarGIT.git
   c234d35..03dea89  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git switch Tugas-finalProject
Switched to branch 'Tugas-finalProject'

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-finalProject)
$ git commit -m "Berhasil Ketujuh"
[Tugas-finalProject ec8d954] Berhasil Ketujuh
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (Tugas-finalProject)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 516 bytes | 516.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/060307Daniel/BelajarGIT.git
   03dea89..4000d7c  main -> main

G@DESKTOP-PQ680AD MINGW64 ~/Documents/KULIAH/Semester 4/web/BelajarGIT (main)
$

