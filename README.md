# Auto_UoA_SCTIA_seminar
This project is for a seminar in continuation techniques and to study their implementation in Auto07p


I don't know if this will help anyone but I'm new to GitHub so I did a quick guide to see how to use it. 

Firstly you'll want to download the desktop GitHub version and create an account (if you don't have one). Then If you are in a mac, open the terminal find a folder where you want to place the project and run the following command:

git clone https://github.com/agir284/Auto_UoA_SCTIA_seminar

This should create a folder with all the files in the GitHub straight into your computer. Then (for those of us who use Sublime) whenever you open a new file make sure you add Folder to project -- using the folder created by the GitHub clone command -- and voila! 


To see all the new files in the GitHub repository: go to the terminal  and use git status to show whats different from your computer and the "cloud". 

Then type git add. This will add all the changes you've made in the repository. For instance, I created a python "hello world" program just to test that everything was running smooth. So I typed (in the terminal): git add test.py. This will make the change but you have to "commit them".

To do so, you type git commit -m "added test.py". You dont have to give it a message (i.e. -m "bla bla") but I did. Note: at this stage this is still not synced up! 

To do so. type: "git push".

Now, everyone in the repository can "pull" the new data that someone synced by typing(in the terminal): git pull.

NOTE: THIS WILL ONLY WORK WHEN YOU'RE IN THE DIRECTORY OF THE REPOSITORY.

Heres a nice thing: 
These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

