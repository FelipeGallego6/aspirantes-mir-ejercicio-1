Last login: Wed Mar  1 18:09:28 on ttys000
FelipeGallego@MBP-de-Felipe ~ % pwd
/Users/FelipeGallego
FelipeGallego@MBP-de-Felipe ~ % mkdir ejercicios
FelipeGallego@MBP-de-Felipe ~ % cd ejercicios
FelipeGallego@MBP-de-Felipe ejercicios % code.
zsh: command not found: code.
FelipeGallego@MBP-de-Felipe ejercicios % code.
zsh: command not found: code.
FelipeGallego@MBP-de-Felipe ejercicios % code.
zsh: command not found: code.
FelipeGallego@MBP-de-Felipe ejercicios % pwd
/Users/FelipeGallego/ejercicios
FelipeGallego@MBP-de-Felipe ejercicios % code.
zsh: command not found: code.
FelipeGallego@MBP-de-Felipe ejercicios % code .
FelipeGallego@MBP-de-Felipe ejercicios % clear







FelipeGallego@MBP-de-Felipe ejercicios % mkdir ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios % pwd
/Users/FelipeGallego/ejercicios
FelipeGallego@MBP-de-Felipe ejercicios % .ejercicios1
zsh: command not found: .ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios % ./ejercicios1
zsh: permission denied: ./ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios % /.ejercicios1
zsh: no such file or directory: /.ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios % pwd
/Users/FelipeGallego/ejercicios
FelipeGallego@MBP-de-Felipe ejercicios % cd ejercicios
cd: no such file or directory: ejercicios
FelipeGallego@MBP-de-Felipe ejercicios % cd ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios1 % pwd
/Users/FelipeGallego/ejercicios/ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios1 % mkdir README.md
FelipeGallego@MBP-de-Felipe ejercicios1 % pwd
/Users/FelipeGallego/ejercicios/ejercicios1
FelipeGallego@MBP-de-Felipe ejercicios1 % clear




FelipeGallego@MBP-de-Felipe ejercicios1 % git --version
git version 2.37.1 (Apple Git-137.1)
FelipeGallego@MBP-de-Felipe ejercicios1 % gt --global user.name FelipeGallego6
zsh: command not found: gt
FelipeGallego@MBP-de-Felipe ejercicios1 % git --global user.name FelipeGallego6
unknown option: --global
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
FelipeGallego@MBP-de-Felipe ejercicios1 % git --global user.email felipegallego6@gmail.com
unknown option: --global
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]
FelipeGallego@MBP-de-Felipe ejercicios1 % git config -l
credential.helper=osxkeychain
init.defaultbranch=main
user.name=Felipe.Gallego
user.email=108532309+FelipeGallego6@users.noreply.github.com
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
FelipeGallego@MBP-de-Felipe ejercicios1 % clear

FelipeGallego@MBP-de-Felipe ejercicios1 % cmd
zsh: command not found: cmd
FelipeGallego@MBP-de-Felipe ejercicios1 % $ git config --global user.name FelipeGallego6
zsh: command not found: $
FelipeGallego@MBP-de-Felipe ejercicios1 % git config --global user.name FelipeGallego6
FelipeGallego@MBP-de-Felipe ejercicios1 % git config --global user.email felipegallego6@gmail.com
FelipeGallego@MBP-de-Felipe ejercicios1 % git config -l
credential.helper=osxkeychain
init.defaultbranch=main
user.name=FelipeGallego6
user.email=felipegallego6@gmail.com
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
FelipeGallego@MBP-de-Felipe ejercicios1 % git init ejercicios
Initialized empty Git repository in /Users/FelipeGallego/ejercicios/ejercicios1/ejercicios/.git/
FelipeGallego@MBP-de-Felipe ejercicios1 % ls
README.md	ejercicios
FelipeGallego@MBP-de-Felipe ejercicios1 % git add .
fatal: not a git repository (or any of the parent directories): .git
FelipeGallego@MBP-de-Felipe ejercicios1 % git commit -m "Version Inicial"
fatal: not a git repository (or any of the parent directories): .git
FelipeGallego@MBP-de-Felipe ejercicios1 % clear



FelipeGallego@MBP-de-Felipe ejercicios1 % cmd
zsh: command not found: cmd
FelipeGallego@MBP-de-Felipe ejercicios1 % ls
README.md	ejercicios
FelipeGallego@MBP-de-Felipe ejercicios1 % git init
Initialized empty Git repository in /Users/FelipeGallego/ejercicios/ejercicios1/.git/
FelipeGallego@MBP-de-Felipe ejercicios1 % git add .
error: 'ejercicios/' does not have a commit checked out
fatal: adding files failed
FelipeGallego@MBP-de-Felipe ejercicios1 % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	ejercicios/

nothing added to commit but untracked files present (use "git add" to track)
FelipeGallego@MBP-de-Felipe ejercicios1 % git add ejercicios/
error: 'ejercicios/' does not have a commit checked out
fatal: adding files failed
FelipeGallego@MBP-de-Felipe ejercicios1 % git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
FelipeGallego@MBP-de-Felipe ejercicios1 % git add .
error: 'ejercicios/' does not have a commit checked out
fatal: adding files failed
FelipeGallego@MBP-de-Felipe ejercicios1 % ls -al
total 0
drwxr-xr-x  5 FelipeGallego  staff  160 Mar  1 19:43 .
drwxr-xr-x  3 FelipeGallego  staff   96 Mar  1 19:20 ..
drwxr-xr-x  9 FelipeGallego  staff  288 Mar  1 19:46 .git
drwxr-xr-x  2 FelipeGallego  staff   64 Mar  1 19:22 README.md
drwxr-xr-x  3 FelipeGallego  staff   96 Mar  1 19:39 ejercicios
FelipeGallego@MBP-de-Felipe ejercicios1 % ls
README.md	ejercicios
FelipeGallego@MBP-de-Felipe ejercicios1 % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	ejercicios/

nothing added to commit but untracked files present (use "git add" to track)
FelipeGallego@MBP-de-Felipe ejercicios1 % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	ejercicios/

nothing added to commit but untracked files present (use "git add" to track)
FelipeGallego@MBP-de-Felipe ejercicios1 % cd ejercicios
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Version Inicial"
[main (root-commit) 2ccd88d] Version Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agrega solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % cd README.MD
cd: not a directory: README.MD
FelipeGallego@MBP-de-Felipe ejercicios % CD README.md
/usr/bin/CD: line 4: cd: README.md: Not a directory
FelipeGallego@MBP-de-Felipe ejercicios % cd README.md
cd: not a directory: README.md
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add README.md
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % cd README.md                                     
cd: not a directory: README.md
FelipeGallego@MBP-de-Felipe ejercicios % cd /README.mdE
cd: no such file or directory: /README.mdE
FelipeGallego@MBP-de-Felipe ejercicios % cd /README.md
cd: no such file or directory: /README.md
FelipeGallego@MBP-de-Felipe ejercicios % git branch
* main
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git branch "Agregar solucion primer ejercicio"
fatal: 'Agregar solucion primer ejercicio' is not a valid branch name
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Version Inicial" 
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git branch solucion1
FelipeGallego@MBP-de-Felipe ejercicios % git branch
* main
  solucion1
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agrefar solicion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add README.md
FelipeGallego@MBP-de-Felipe ejercicios % git commit "Agregar solucion primer ejercicio"
error: pathspec 'Agregar solucion primer ejercicio' did not match any file(s) known to git
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add README.md
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git init
Reinitialized existing Git repository in /Users/FelipeGallego/ejercicios/ejercicios1/ejercicios/.git/
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % clean
zsh: command not found: clean
FelipeGallego@MBP-de-Felipe ejercicios % clear

FelipeGallego@MBP-de-Felipe ejercicios % git init
Reinitialized existing Git repository in /Users/FelipeGallego/ejercicios/ejercicios1/ejercicios/.git/
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add README.md
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m"Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git config -l
credential.helper=osxkeychain
init.defaultbranch=main
user.name=FelipeGallego6
user.email=felipegallego6@gmail.com
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
FelipeGallego@MBP-de-Felipe ejercicios % ls
README.md
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m 'Agregar solucion primer ejercicio'
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git log
commit 2ccd88df3669447e7fd77098b267cd7e4bbf681a (HEAD -> main, solucion1)
Author: FelipeGallego6 <felipegallego6@gmail.com>
Date:   Wed Mar 1 19:53:37 2023 -0500

    Version Inicial
FelipeGallego@MBP-de-Felipe ejercicios % git add 'Agregar solucion primer ejercicio'
fatal: pathspec 'Agregar solucion primer ejercicio' did not match any files
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add README.md
FelipeGallego@MBP-de-Felipe ejercicios % git commit-m "Agregar solucion primer ejercicio"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
	commit-tree
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % ls
README.md
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git log
commit 2ccd88df3669447e7fd77098b267cd7e4bbf681a (HEAD -> main, solucion1)
Author: FelipeGallego6 <felipegallego6@gmail.com>
Date:   Wed Mar 1 19:53:37 2023 -0500

    Version Inicial
FelipeGallego@MBP-de-Felipe ejercicios % git add .
FelipeGallego@MBP-de-Felipe ejercicios % git commit -m "Agregar solucion primer ejercicio"
[main 0eebcfe] Agregar solucion primer ejercicio
 1 file changed, 13 insertions(+)
FelipeGallego@MBP-de-Felipe ejercicios % git status
On branch main
nothing to commit, working tree clean
FelipeGallego@MBP-de-Felipe ejercicios % git log
commit 0eebcfe2fc798f399f8ccb6b845e485a7b9ad18c (HEAD -> main)
Author: FelipeGallego6 <felipegallego6@gmail.com>
Date:   Thu Mar 2 23:23:57 2023 -0500

    Agregar solucion primer ejercicio

commit 2ccd88df3669447e7fd77098b267cd7e4bbf681a (solucion1)
Author: FelipeGallego6 <felipegallego6@gmail.com>
Date:   Wed Mar 1 19:53:37 2023 -0500

    Version Inicial
FelipeGallego@MBP-de-Felipe ejercicios % 
  [Restored 3/03/2023, 12:28:39 PM]
Last login: Fri Mar  3 12:28:36 on console
Restored session: Thu Mar  2 23:47:15 -05 2023
FelipeGallego@MBP-de-Felipe ejercicios % 
