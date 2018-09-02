# Basic git command lines

* After installing git
$ git config --global user.name "`Your Name`"
$ git config --global user.email `your@email.com`

* Creating a repository and connecting it to a remote server
$ mkdir `repository`
$ git init
$ git remote add origin `server`

* Or just cloning a existing repository
$ git clone `username@host:path`

* Adding a file, commiting changes and updating the remote repository
$ git add `file`
$ git commit -m "`Description of the changes you've made in the files added`"
$ git push

* Updating from the remote repository
$ git pull

* Creating a new branch and pushing its changes to the remote repository
$ git checkout -b `branch-name`
$ git push origin `branch-name`

* List of available git commands
$ git help -a
