# learning-git

This repo was used to learn git from Amigoscode

# Outline
- [Terms](#terms)
- [iTerm2](#iterm2)
- [IntelliJ](#intellij)
- [git](#git)
- [vim](#vim)
- [Unix](#unix)
- [tree](#tree)


# Terms
**Pull request**
* make a change on feature branch
* create pull request in Github
* someone reviews and approves
* auto merge to master


**Rebase**
* What is rebase?
* master on bottom
* new commits on top
* What is squash?

**HEAD:** the current commit in your local repo you are looking at
* current change = local commit
* incoming change = remote commit 



# iTerm2
* cmd+d == new terminal on side
* cmd+t == new terminal tab
* ctrl+a == front
* ctrl+e == end
* alt+b == go back
* alt+f == go forward
* ctrl+w == delete word backwards

# IntelliJ
* cmd+option+v = extract to variable
* shift+F6 = rename
* cmd+option+L = format code
* shift+ctrl+space = autocomplete options 

# GIT
* git log --oneline -5
* git checkout <myfile name> = discard changes 
* git branch -a
* git remote -v
* git amend -m <“my newly amended message”>
* git checkout -b <my_new_branch> = create a new branch and change to it
* git push -u origin <new_branch_name> == push new branch to github
* git push origin main -f == overwrite origin	
* git branch -d <my_local_branch> = delete local branch
* git show
* git rebase -i HEAD~3 = squash
* git rebase main
	* fix conflicts
	* git rebase --continue
	* git push -f   (only do -f if needed)

# VIM
* :q! = quit without saving
* :wq = write quit
* i=insert mode
vim index.js = edit file
* w = move by word forward
* b = back, move by word back
* 0 = move to index 0, beginning of line 
* $ = move to end of line
* gg = beginning of line
* G = end of file
* { = move by spaces up
* } = down
* 6gg = move to a specific line 
* vim +20 <classes.js>
* esc = command mode
	* u = undo
	* ctrl+r = redo
  *	a = move cursor to letter after and start writing 
	* shift+o = move cursor to line above and start writing
	* shift+a = move cursor to end of line and start writing
	* dd = delete/cut entire line
	* dw = delete/cut word
	* db = delete/cut beginning
  * p = paste
  

* move in 4 directions
   k
h    l
   j = jump down


# UNIX
* curl -0 <https://raw.githubusercontent.com/amigoscode/.../classes.js>
* grep  -rni <”#end”> . = search for #end, display row number and search is case-insensitive
* man find = manual for find
* find . -name <query-1.sql> == find a file named query-1.sql 
* find . -iname <“main*”> == find all files with name case insensitive
* find . -iname <“*.css”> == find a file with name  .css case insensitive
* find . -name <“MAIN*”> -delete == find and delete (files and folders) that meet condition
* cp <query-1.sql> <query-copy.sql> == make a copy of a file called query-copy.sql
* cp -r <tutorial> <tutorials-copy> == make a copy of a directory, recursively
* cp <*.sql> = copy everything with 
* echo “overwrite something” > query-1.sql == overwrite file // note: > 
* echo “append something” >> query-1.sql == append to file // note: >> 
* cat index.js = view contents of file
* mv <main.go> <tutorials> == move file into folder
* mv <tutorials/main.go> . == move file up one level
* mv tutorials examples == rename a folder
* touch query.sql == create a file 
* cd ~	== go to root
* rm -r == remove folder and subfolders

# TREE
* tree <example> = see folder structure
* less <test.js> = paginate through with space
* head <test.js> = see the beginning of file
* tail <test.js> = see tail of file
	

# Linkz
* https://amigoscode.com/courses/1317178/lectures/30664230
* https://github.com/fefong/markdown_readme/blob/master/README.md#titles
