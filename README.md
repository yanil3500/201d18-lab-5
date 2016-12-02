# Assignment Overview: Lab for Class 5

There are two parts to your lab assignment, and each is in a different assignment in Canvas:

### First Part: Over the weekend

One of them is a weekend project: put finishing touches on your About Me project and get it deployed. This will be due at 11:59pm on Sunday evening. The more time you spend with this, the better you'll get at CSS styling, but keep in mind that you also have readings to do and need to get some rest and relaxation in as well! We have a HUGE week next week, so be sure to come into it refreshed and ready.

---

### Second Part: In lab today

Today in lab you will collaborate with your partner in a new GitHub repo, and create solutions to some little code problems.

**Be sure to follow instructions carefully and meticulously.**

Here are a couple of things to keep in mind:

* While you are in the process of writing and testing your code problems, every function should be called by hand from the console. This is to give you additional practice using the console and practice efficient app-switching processes.
* Create a new branch for each code problem, and merge each branch into *master* on GitHub (and then pull back into master on your laptops!) when the problem is completed. Do the problems in order. Don't forget to pull the updated master branch from GitHub into your local master branch ***each*** time, before creating the branch for the next problem. Steps for this process will be given at the bottom of this document.

---
### HTML and JS setup: starter code!
You are being given starter code for today, in the index.html and app.js files inside of this directory. The success of your code will be determined by whether it passes tests that are in tests.js file. You do not need to do anything with tests.js, though you should take a look at it to see how it works.

Submission instructions are in the Canvas assignment as usual.

---
### Git process for this lab

Git & GitHub Team Workflow
=================

* One of the partners in your pair should go to this repo and fork it.

* That person then goes into the "Settings" tab of their fork of the lab repo and set their partner as a collaborator. That means both members of the pair will have equal rights to push to the repo and also perform merges.

* Both team members should now clone the repo to their individual laptops.

* You will be solving four code problems together, each of which involves writing and testing a function.

* The partners will alternate on whose laptop the work is done. Once a single problem is completed, that problem must be ACPed to the shared repo.

* The other partner then does a `git pull origin master`, creates a new branch for the next problem, and then the partners collaborate on solving the problem. Following is the command sequence listed below. Deviate from it at your own peril.

## When you start working on a new problem...
* Start from an up-to-date **master** branch by making certain that you've done a `git checkout master` and then a `git pull origin master` to sync the local repository with the version on GitHub
*  Create a new feature branch with `git checkout -b <branchname>`  
* Do work on your feature branch to solve the problem, and then **add**, **commit**, and **push** (ACP FTW!)  
 * `git add .`  
 * `git commit -m <useful message in quotes>`   
 * `git push origin <feature_branch_name>`
* On GitHub...
 * Create a Pull Request (PR) for that branch on GitHub
 * Have your partner review the code in the PR and merge it into master
 * Both members of the team then need to `git checkout master` and then a `git pull origin master` to sync the local repository with the version on GitHub
