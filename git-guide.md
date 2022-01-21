This is a guide for using git and GitHub. This will include a command with a brief definition of what it does and a sample of how to use it.

COMMAND LINE GIT
1. status
	- shows status of the local repository. This status includes:
		- number of loacal commits that have not been synced with remote (GitHun)
		- list of files in local folder than are NOT being tracked by git
		- list of files in local folder that have changes that need to be committed
	- how to use:  git status

2. clone 
	- creates a copy of a remote repository on your local machine. 
	- how to use: git clone [repository link]

3. add
	- selects a file and moves it to 'stage' it for the next commit
	- git add and git commit work together 
	- how to use: git add [filename]

4. rm
	- can be used to remove files or directories
	- how to use: rm [file/directory name]

5. commit
	- captures snapshot of project's currently staged changes
	- usually git add is before git commit
	- how to use: git commit -m "message"

6. push
	- pushes commits from local branch in your local git repository to remote repository
	- how to use: git push

7. fetch
	- downloads contents from a remote repository 
	- how to use: git fetch [remote branch or just by itself]

8. merge
	- combines multiple sequences of commits to one history
	- how to use: git merge [branch]

9. pull
	- fetches new commits and merges them into local branch
	- how to use: git pull [repository]

10. branch
	- can list, create, or delete branches
	- how to use: git branch [branch name]

11. checkout
	- navigates between branches created by git branch
	- how to use: git checkout [branch]

GIT FILES & FOLDERS
1. .git folder
	- contains all info necessary for project and stores commit history
	- how to find: cd .git

2. .gitignore file
	- a text file that tells Git which files or folders to ignore a project
	- how to find: cd .gitignore 

GITHUB 
1. pull requests
	- can assist to all collaborate on changes to a repository. Proposed on a branch, which ensures the default branch contains finished and approved wotk
	- can create pull requests through github

2. SSH authentication to repositories
	- to clone ssh to repository. 
