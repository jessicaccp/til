# Basic git command lines

* **After installing git** <br />
$ git config --global user.name "`Your Name`" <br />
$ git config --global user.email `your@email.com`

* **Creating a repository and connecting it to a remote server** <br />
$ mkdir `repository` <br />
$ git init <br />
$ git remote add origin `upstream`

* **Or just cloning a existing repository** <br />
$ git clone `username@host:path`

* **Adding a file, commiting changes and updating the remote repository** <br />
$ git add `file` <br />
$ git commit -m "`Description of the changes you've made in the files added`" <br />
$ git push

* **Updating from the remote repository** <br />
$ git pull

* **Creating a new branch and pushing its changes to the remote repository** <br />
$ git checkout -b `branch-name` <br />
$ git push origin `branch-name` <br />

* **List of available git commands** <br />
$ git help -a
