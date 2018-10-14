# devops

# Git commands
Git task	Notes	Git commands


### git config --global user.name "Sam Smith"

### git config --global user.email sam@example.com

Create a new local repository	 	

### git init
Check out a repository	Create a working copy of a local repository:	

### git clone /path/to/repository

For a remote server, use:	
### git clone username@host:/path/to/repository

Add files	Add one or more files to staging (index):	

### git add <filename>
*Commit	Commit changes to head (but not yet to the remote repository):	

### git commit -m "Commit message" Commit any files you've added with git add, and also commit any files you've changed since then:	

### git commit -a
Push	Send changes to the master branch of your remote repository:	git push origin master

