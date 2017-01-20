# github-tutorial


#### Forking freeCodeCamp

1. Go to the top level github-tutorial repository: <https://github.com/alemneh/github-tutorial>
2. Click the "Fork" Button in the upper right hand corner of the interface.
3. After the repository has been forked, you will be taken to your copy of the tutorial repo at `yourUsername/github-tutorial`

#### Cloning Your Fork

1. Open a Terminal / Command Line / Bash Shell in your projects directory (_i.e.: `/yourprojectdirectory/`_)
2. Clone your fork of github-tutorial

```shell
$ git clone https://github.com/yourUsername/github-tutorial.git
```

##### (make sure to replace `yourUsername` with your GitHub Username)

This will download the entire tutorial repo to your projects directory.

#### Setup Your Upstream

1. Change directory to the new github-tutorial directory (`cd github-tutorial`)
2. Add a remote to the official github-tutorial repo:

```shell
$ git remote add upstream https://github.com/alemneh/github-tutorial.git
```

Congratulations, you now have a local copy of the github-tutorial repo!

### Create A Branch

Before you start working, you will need to create a separate branch specific to the issue / feature you're working on. You will push your work to this branch.

#### Naming Your Branch

Name the branch something like `fix/xxx` or `feature/xxx` where `xxx` is a short description of the changes or feature you are attempting to add. For example `fix/email-login` would be a branch where you fix something specific to email login.

#### Adding Your Branch

To create a branch on your local machine (and switch to this branch):

```shell
$ git checkout -b [name_of_your_new_branch]
```

Check you are in the correct branch:

```shell
$ git branch
```
(It should show all the branches and the one with the star is the one you are on)

Open the current directory in your faviorite text editor:

```shell
$ atom .
```
Make your changes and save the files.

Then add your changed files to staging:

```shell
$ git add .
```

Then commit your changes:

```shell
$ git commit -m "Leave a comment about the change"
```


and then push your branch to GitHub:

```shell
$ git push origin [name_of_your_new_branch]
```
