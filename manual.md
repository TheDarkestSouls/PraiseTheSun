# Git manual
## Main command

* __git config --global user.name "name"__ - set a user name
* __git config --global user.email "email"__ - set an email adress
* __git init__ - initialization of a local repository
* __git status__ - current state
* __git add__ - add file(s) to a following commit
* __git commit -m'message'__ - create commit
* __git commit --amend -m'message'__ - correct last commit name
* __git log__ - show history of commits with their hash-codes
* __git log --oneline__ - show brief history
* __git log --graph__ - show history graphically
* __git log --graph --oneline__ - brief graphical history
* __git checkout "commit_hash-code"__ - switch commit from one to another
* __git checkout master__ - get back to actual state and proceed
* __git diff__ - show difference beetween curent and commited file
* __git branch__ - show all branches and which you are currently on
* __git branch "new_branch_name"__ - add new branch
* __git checkout "branch_name"__ - switch to another branch
* __git branch -d "branch_to_delete"__ - delete branch
* __git merge "branch_name"__ - merge another branch with which you are currently on
* __git merge --abort__ - abort the merge before commiting
* __git clone "repo_link"__ - clone remote repo to a local
* __git pull__ - download and merge all data from a personal account repository
* __git push__ - send local repo version to a personal remote repo __(NEED AUTHORIZATION on a remote repository)__

## Work with github

### Push and pull operations

1. Create account on github.com.
2. Create local repository.
3. "Make a friendship" beetween local and remote repository. Github will assist with that.
4. Send (push) a local repository to a remote (on github). __Authorization__ on a remote account may be needed.
5. Make changes from a remote PC.
6. Download (pull) actual state from a remote repo.

### Pull requests

1. Make a fork of a repository which we interested in.
2. Make __git clone__ for a local version of this repository.
3. Create a branch with suggested changes.
4. Make all changes in only this branch.
5. Send all changes to your account (__push__).
6. In the github window a pull request option appears(see below)

![request1](request1.bmp)

![request2](request2.bmp)

![request3](request3.bmp)




---

## Markdown syntaxis


* '# Header' - _Mark header. Numbers of '#' define level of header (6 maximum)_
* '= or -' - _Use(3 times min) to mark 1st and 2nd level header_
* \*\***bold text** \*\* _or_ \_\___bold text__ \_\_
* \**italic*\* _or_ \__italic_\_
* \*\*\****bold italic***\*\*\*
* \~\~~~struck out text~~\~\~
* \* line - _unnumbered lists, symbol(*)_
* 1, 2, 3 - _numbered lists_

## Work with images

* To add image put an image file (jpg etc) to the working directory and use command: \!\[some text\]\(filename\).
![conflict](Conflict.bmp)
## Work with links
There are few ways to create links:

* [inline style link](https://www.wikipedia.org/)
* [inline style link with title](https://www.wikipedia.org/ "Wikipedia's Homepage")
* [reference style link][Arbitrary case-insensitive reference text]*
* [relative reference to a repository file](https://github.com/TheDarkestSouls/PraiseTheSun)
* [Numbers can be used for reference-style link definitions][1]*
* [link text itself]*

\* Reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: https://www.nasa.gov/
[link text itself]: https://www.fourseasons.com/

## Work with tables
Tables aren't part of the core Markdown spec, but they are part of GFM and Markdown Here supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

Colons can be used to align columns.

| I    | Am  | GitMaster  |
| -----|:---:| ----------:|
| can  | use | Markdown   |
| know | all | commands   |
| easy | as  | a pie      |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


## Quotes
I know some quotes but i don't think you'd like them.

### _"May the force be with you"_
Star Wars (1977)
___
### _"My mama always said life was like a box of chocolates. You never know what you're gonna get."_
Forrest Gump (1994)
___
### _"I'm gonna make him an offer he can't refuse."_
The Godfather (1972)
___
### _"A boy's best friend is his mother."_
Psycho (1960)
___
### _"You've got to ask yourself one question: 'Do i feel lucky?' Well, do ya, punk?"_
Dirty Harry (1971)

## Summary
I know all the main git commands, and about markdown too.
Maybe one day I'll make a Terminator. 

