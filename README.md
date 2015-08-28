# Description

dbtester is a small program to run several kinds of test again a database, for example, connectivity and performance test.


# Notes for using Bitbucket git service

I'm new to programming and this is my first project on Bitbucket, so I put some usage hints here.

## Push to Bitbucket

Set up Git on your machine if you haven't already.

	mkdir /path/to/your/project
	cd /path/to/your/project
	git init
	git remote add bitbucket https://username@bitbucket.org/username/dbtester.git

Create your first file, commit, and push

	git add .
	git commit -m 'Initial commit with contributors'
	git push -u bitbucket master

## Push to Github

	git remote add github https://github.com/username/dbtester
	git push -u github master
