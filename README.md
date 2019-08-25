# training
## training with Flanklin started on the 18 Aug 2019 @DoSpace
1. Install VS Code
- https://code.visualstudio.com/docs/?dv=osx

2. git setup
- create github account
- create repository
- on PC, 
	- cd to right master directory
	- echo "# training" >> README.md
	- git config --global --edit
	- git commit --amend --reset-author
	- git init
	- git add .
	- git commit - "Initialization"
	- git remote add origin https://github.com/DaveW86/training.git
	- git push -u origin master
	- enter credentials
- set auto login on github by ssh auth, 
  - on PC, 
  	- check existing ssh key : cd ~/.ssh
	  - if not
		- ssh-keygen
		- pbcopy < ~/.sshid_rsa.pub
  - copy the public key on github by create new key @https://github.com/settings/keys
3. Install https://nodejs.org/en/ and NPM

