# Set Up Git


## Installation
1. Install git from [Git for Windows](https://gitforwindows.org/) or using the
   python package manager `pip` by executing `pip install git`

## First Time Configuration ### Set Credentials

The `git config` sub-command is used to set user credentials. 

There are two modes `git config --global` and `git config --local`(default): 
	1. If you only have one github account, use the `--global` option to set
	   your credentials across all repositories.
	2. If you use the `--local` option you will have to enter your
	   credentails(once, during set up) for each repository.

	Set you username and email like so: 
	```
	> git config --global user.name "[Your User Name]" git config --global
	> user.email "[yourusername]@github.com"
	```

Make sure to add the email provided by GitHub. You can look for it in your
settings:[Github Email Settings](https://github.com/settings/emails)

### Push Your First File

	1. Create a repository in your github and follow the instructions.
	2. If everything is working it, there should be a readme.md file in your
	github repo

### Credential Management

If you don't want to enter your username password everytime you push to a
repository

