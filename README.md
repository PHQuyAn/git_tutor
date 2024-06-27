<h3><b> create new repository on the command line </b> </h3>  
```
    git init
    git add 'file'
    git commit -m "message"
    git branch -M main
    git remote add origin "link to github repo"
    git push -u origin main
```

<h3><b> push existing repository from the command line </h3></b>  
```
    git remote add origin "link to github"
    git branch -M main
    git push -u origin main
```

Know the information of user:  
```	
    git config --list
```

Know the username:
```
	git config user.name
```

Know the email:
```
	git config user.email
```

Change the username or email:  
```
    git config --global user.name "new name"
    git config --global user.email "new email"
```

| Command                 |          Use for     |
|------------------------ |----------------------|  
|git config -h            |	help with git config |
|git status			      | The status of repository |
|git add	'file'		  |	Add a file and Track this file |
|git rm --cached 'file'   |	Remove and untrack file |
|git add --all			  | Track all files|
|git add --A              | |
|git add .				  | |
|git commit -m "message"  |	commit a file (take a message that we will push or change a file)|
|git diff				  |	check the different of two files|
|git restore --staged 'file'|remove file from staging ("previous file added")|
|git commit -a -m		  |	add and commit file |
|git rm "file"			  |	remove / delete file|
|git log -p			      |	view changes in commits|
| git restore			  | return back (undo)|
|git log				  |	see the history of commits|
|git commit -m "file" -amend | change the message|
|git branch "name branch" |	create new branch|
|git branch			    |	see all branch and current branch|
|git switch "name branch" | switch to other branch|
|git merge -m "message" file  |	merge the change from new branch to old branch
|git branch -d "name branch"	    |			delete branch
|git switch -c "name branch" | creating a new branch and switch to it|
|git branch -M main	| set target branch is 'main' branch|
|git push -u origin main | push all files to github except ignore files on current branch| 
|git push -all | push all files every branchs
|git fetch |download all the history from remote tracking branches
|git pull	'remote' |	download the content from a remote repository
|git remote add origin https://github.com/username |      connect to the repository on github|  

To ignore files --> Create .gitignore file
			' *.txt ' '*.extension'
