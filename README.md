<p align="center">
  <h1 align="left">Github Workflow</h1>
</p>
<br />

## About The Github Workflow

Our workflow in github for modular, progressive approach and readiness for the future huge project. The early we start, the better. In this section, you'll learn about the basics and foundation of getting used to `git` commands. There are a few we need to learn, others will come along the way.

## How to start a github project

To start a project, you can simply create a sample files you want to push on Github. Once that is done, create a repository in Github and just follow their instructions for your first push. 

## Continous deployment

You'll learn two types of levels you need to keep in mind, one for basic projects and another for enterprise project. 

### Basic project:
* git add .
* git commit -m "first commit"
* git push

If you encountered any problems during push, simply read the instructions provided. In any ways, that's the start of learning.

### Advanced projects:

Straightforward push is not ideal like you used in basic projects. You have to be open minded to all scenarios you might encounter in the future. Problems, bugs, features, enhancements, and others. You have to think as wide as you can to keep track to any updates of your application. History is very important.

1. Commit all changes:
* `git add .`
* `git commit -m "_what you're working on_"`

First, always commit your changes.

2. Make sure you have the latest files from `main` branch
* `git checkout -b feature/name`

Make sure everytime you want to push something, create a branch of your own always. Don't just push in your `main` or `master` branch. And avoid hard editions or direct commits in your repo. E.g., adding files in `main` branch, add 1 line of code.

* `git checkout main` 
* `git pull`
* `git add .`
* `git commmit -m "_commit_"`

Why pull main and commit changes from main? This is required to make sure you're ahead from `main` branch. 

3). Merge your branch to main

* `git merge main _branch_`

If there any conflict, make sure you fix it. To fix it, always read what the code is all about and what conflicted from other people's work. Talk to your team about it, or accept other people's incoming change. _You'll be familiar with this once you've encounter one_

4). Push your branch

* `git push` _if its your first time pushing your branch, read the instructions_

Why not push directly to main? Just don't :) 

5). Create a Pull Request, see it here [how to create a pull request](https://opensource.com/article/19/7/create-pull-request-github). _If you'll see a word says "Able to merge" then your branch is in best state. Congrats!_

## Conclusion

These are the basic commands you'll ever need, once you master this, you will not going to have any problems in the future. Everything can be searched in the web, any answers to your problem related to git commands are not impossible to solve. There are a lot of intelectual guys out there that can solve your problems. [stackoverflow](http://stackoverflow.com/). 

