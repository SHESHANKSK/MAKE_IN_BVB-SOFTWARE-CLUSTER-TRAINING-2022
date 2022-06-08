# TS 01: INSTALLING GIT AND CREATING A GITHUB ACCOUNT

## Agenda of Today's Session:
1. Download and Install Git
2. Hands on Git Bash Interface
3. Basic Git Commands
4. Create a repository on your Local Machine
5. Create a Github Account
6. Generating the Personal Access tokens
7. Establishing the Connection between Local and Remote repository
8. Pushing files to Github
<hr>

### 1. Download and Install Git
Go to the following website
> [Download Git](https://git-scm.com/downloads)

a. The following web page will appear
![image](https://user-images.githubusercontent.com/62549471/172558443-865523d5-c637-435c-a500-d5e41c26751b.png)
b. Now choose the version according to your requirements
![image](https://user-images.githubusercontent.com/62549471/172558776-5e025ea0-ca81-4939-b29d-bdc36f589c40.png)
c. Click on Next to Complete the Installation Process
![image](https://user-images.githubusercontent.com/62549471/172559098-965be775-a35c-430d-a94d-54ac7f8ef844.png)

### 2. Hands on Git Bash Interface
Step 01: Open the Git Bash
![image](https://user-images.githubusercontent.com/62549471/172559418-7add0982-0faa-4ea4-8571-a6e43b194155.png)

Step 02: Check the git Version
```cmd
git --version
```
Step 03: Accessing the git --help command
This command gives us information about all the available commands 
```
git --help
```
Output:

```cmd
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
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
```



