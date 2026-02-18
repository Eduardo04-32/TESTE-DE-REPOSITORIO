# HOLA MUNDO, BIENVENIDO A ESTE REPOSITORIO QUE NO TIENE NADA DEL OTRO MUNDO 



AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~
$ cd documents

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents
$ git clone https://github.com/Eduardo04-32/TESTE-DE-REPOSITORIO.git
Cloning into 'TESTE-DE-REPOSITORIO'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents
$ cd TESTE-DE-REPOSITORIO

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        arquivoooo.txt

nothing added to commit but untracked files present (use "git add" to track)

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git add .

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   arquivoooo.txt


AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git commit -m "Criado meu arquivo, não fiz muito luiz!!! "
git commit -m "Criado meu arquivo, não fiz muito luizgit status! "
[main 7c9bc2c] Criado meu arquivo, não fiz muito luizgit status!
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 arquivoooo.txt

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git log
commit 7c9bc2cf76a1fc8ae03ce91084ad559a7e8af40f (HEAD -> main)
Author: Eduardo04-32 <jesus.sanchez32.12@gmail.com>
Date:   Wed Feb 18 14:18:25 2026 -0300

    Criado meu arquivo, não fiz muito luizgit status!

commit 2a7cbbf1d37bf0fad205102b11fe84820579ad7c (origin/main, origin/HEAD)
Author: Eduardo04-32 <jesus.sanchez32.12@gmail.com>
Date:   Wed Feb 18 13:53:53 2026 -0300

    Initial commit

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git push origin main
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Eduardo04-32/TESTE-DE-REPOSITORIO.git
   2a7cbbf..7c9bc2c  main -> main

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git push origin main
Everything up-to-date

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git bramsh
git: 'bramsh' is not a git command. See 'git --help'.

The most similar command is
        branch

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git branch
* main

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git branch "branch-teste"

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (main)
$ git checkout branch-teste
Switched to branch 'branch-teste'

AzureAD+JESUSSANCHEZ@SLE212029 MINGW64 ~/documents/TESTE-DE-REPOSITORIO (branch-teste)
$
