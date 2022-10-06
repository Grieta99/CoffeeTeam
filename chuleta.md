### Chuleta de control de versiones con git


usuario@P10L214 MINGW64 /c/Users/usuario
$ cd Documents/Processing/

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Processing
$ cd..
bash: cd..: command not found

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Processing
$ cd ..

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ cd Documents/Processing/
bash: cd: Documents/Processing/: No such file or directory

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ cd Documents/processing/
bash: cd: Documents/processing/: No such file or directory

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ cd Documents/Proyectos/
bash: cd: Documents/Proyectos/: No such file or directory

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ CD
bash: CD: command not found

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ cd ..

usuario@P10L214 MINGW64 /c/Users/usuario
$ cd Documentos/
bash: cd: Documentos/: No such file or directory

usuario@P10L214 MINGW64 /c/Users/usuario
$ cd Documents/

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ cd Pro
Processing/ Proyectos/

usuario@P10L214 MINGW64 /c/Users/usuario/Documents
$ cd Proyectos

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos
$ cd procesing/

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git branch
* damariz
  main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git branch --all
* damariz
  main
  remotes/origin/damariz
  remotes/origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$




usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git fetch
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 7 (delta 1), reused 3 (delta 1), pack-reused 0
Unpacking objects: 100% (7/7), 1.57 KiB | 27.00 KiB/s, done.
From https://github.com/Damarizllm/globos_procesing
 * [new branch]      AntonioP   -> origin/AntonioP
   db990f5..fdb9e6a  main       -> origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git branch --all
* damariz
  main
  remotes/origin/AntonioP
  remotes/origin/damariz
  remotes/origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git merge
Already up to date.

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git branch --all
* damariz
  main
  remotes/origin/AntonioP
  remotes/origin/damariz
  remotes/origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git log
commit 89ec1e8c7a3a46ac14b1af807982a789c03c01d0 (HEAD -> damariz, origin/damariz)
Author: unknown <damariz llanes michel>
Date:   Thu Sep 29 15:07:55 2022 +0200

    fondo cambiado

commit db990f506232c84a0e3c628e58adc084fcc7b12d (main)
Author: unknown <damariz llanes michel>
Date:   Thu Sep 29 14:21:23 2022 +0200

    ventana mas pequeña

commit 5034c4afa5ac8872d79c17d7d4659694508161cc
Author: unknown <damariz llanes michel>
Date:   Thu Sep 29 14:18:26 2022 +0200

    versionj inicial

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$
























usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git fetch
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 7 (delta 1), reused 3 (delta 1), pack-reused 0
Unpacking objects: 100% (7/7), 1.57 KiB | 27.00 KiB/s, done.
From https://github.com/Damarizllm/globos_procesing
 * [new branch]      AntonioP   -> origin/AntonioP
   db990f5..fdb9e6a  main       -> origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git branch --all
* damariz
  main
  remotes/origin/AntonioP
  remotes/origin/damariz
  remotes/origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git merge
Already up to date.

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git branch --all
* damariz
  main
  remotes/origin/AntonioP
  remotes/origin/damariz
  remotes/origin/main

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git log
commit 89ec1e8c7a3a46ac14b1af807982a789c03c01d0 (HEAD -> damariz, origin/damariz)
Author: unknown <damariz llanes michel>
Date:   Thu Sep 29 15:07:55 2022 +0200

    fondo cambiado

commit db990f506232c84a0e3c628e58adc084fcc7b12d (main)
Author: unknown <damariz llanes michel>
Date:   Thu Sep 29 14:21:23 2022 +0200

    ventana mas pequeña

commit 5034c4afa5ac8872d79c17d7d4659694508161cc
Author: unknown <damariz llanes michel>
Date:   Thu Sep 29 14:18:26 2022 +0200

    versionj inicial

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git status
On branch damariz
Your branch is up to date with 'origin/damariz'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   globos_000.pde

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        sketch.properties

no changes added to commit (use "git add" and/or "git commit -a")

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git commit -m "cambio de forma"
On branch damariz
Your branch is up to date with 'origin/damariz'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   globos_000.pde

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        sketch.properties

no changes added to commit (use "git add" and/or "git commit -a")

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git add globos_000.pde

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git commit -m "cambio de forma"
[damariz 36f06b7] cambio de forma
 1 file changed, 3 insertions(+), 1 deletion(-)

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git pull
Already up to date.

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$ git status
On branch damariz
Your branch is ahead of 'origin/damariz' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        sketch.properties

nothing added to commit but untracked files present (use "git add" to track)

usuario@P10L214 MINGW64 /c/Users/usuario/Documents/Proyectos/procesing (damariz)
$
