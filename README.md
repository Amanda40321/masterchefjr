
ozysh@LAPTOP-GK89BG45 MINGW64 ~
$ pwd
/c/Users/ozysh

ozysh@LAPTOP-GK89BG45 MINGW64 ~
$ cd desktop

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop
$ ls
 7c04b825-1951-4683-9c7d-8f8e8dc75d3d.jpg         'Removed Apps.html'
'Ebook pub'/                                      'Visual Studio Code.lnk'*
'Ebook_Publishing_MadDownloadable_Proof (2).PDF'   Zoom.lnk*
'Kindle Create.lnk'*                               desktop.ini
'OneDrive - Shortcut.lnk'*                         t.rex-/
'Personal - Edge.lnk'*

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop
$ mkdir MyRecipes

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop
$ cd MyRecipes

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes
$ git
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes
$ git https://github.com/Amanda40321/masterchefjr.git
git: 'https://github.com/Amanda40321/masterchefjr.git' is not a git command. See 'git --help'.

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes
$ git init
Initialized empty Git repository in C:/Users/ozysh/Desktop/MyRecipes/.git/

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git add README.md

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git ingredient.md
git: 'ingredient.md' is not a git command. See 'git --help'.

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git add ingredient.md

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git config --global user.name "Amand40321"

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ozysh@LAPTOP-GK89BG45.(none)')

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git config --global user.name "Amand40321"

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$ git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ozysh@LAPTOP-GK89BG45.(none)')

ozysh@LAPTOP-GK89BG45 MINGW64 ~/desktop/MyRecipes (master)
$
