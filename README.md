# Overview

## Learners with no command line experience

1. [collaborate](#collaborate-together-on-your-groups-git-repo) on an existing repo using only the github website
1. brief [intro to command line](#command-line-concepts)
1. [start new repo](#start-a-fresh-repo) locally and putting it on github
1. [practice collaboration](#practice-collaboration-with-each-others-repos) on each other's repos

## Learners with command line experience

1. [collaborate](#collaborate-together-on-your-groups-git-repo) on an existing repo using git locally
1. [start new repo](#start-a-fresh-repo) locally and putting it on github
1. [practice collaboration](#practice-collaboration-with-each-others-repos) on each other's repos
1. lightning talks on advanced [topics collected throughout](#throughout)

# The Plan

## Entrance

Check in when you arrive and let us know if you're comfortable with Git on Windows, and if you prefer students who already have command-line experience. The students without command-line experience will have a modified curriculum that will include an introduction to using the command-line.

As learners come in, we will help them with [setup](./setup.md) if needed and direct them to you. Get to know why they are interested in learning Git, what they do, and what they've heard about Git.  Introduce yourself and why you use Git. Once you have about 5 learners, you can begin to lead them through the curriculum.

## Curriculum

### Collaborate together on your groups' git repo
  * ~ 0.5 hrs - 1.5 hrs
  * a repo of [recipes](https://github.com/codeparkhouston/recipes)
    * We will set up a clean repo when you arrive
    * Add your group members as collaborators

#### Learners with no command line experience
*will do this within the GitHub website*

##### Concepts

1. Branching
1. Commiting, and writing commit messages
1. PRs
1. Review, diffing and merging
1. Master branch
1. Issues
1. Merge conflict
  * Resolved by mentor while showing learners

#### Learners with command line experience
*will do this in the command line*

##### Concepts
All of the above plus

1. Local vs. remote
1. Cloning
1. Git checkout/branching locally
1. Staging files/git add
1. Pushing
1. Pulling

### Start a fresh repo
  * ~ 0.5 hrs - 1.5 hrs

#### Learners with no command line experience
will be introduced to the command line

##### Command line concepts

1. What is it?
1. Paths
1. Commands
  * `ls`
  * `mkdir`
  * `pwd`
  * `cd`

##### Git concepts

1. `git init`
1. Local vs remote
1. `git push`

#### Learners with command line experience
*will do this in the command line*

##### Concepts

All of the above

### Practice collaboration with each other's repos

Pair up and practice the following:

1. Cloning
1. Forking
1. How to add collaborators
1. Resolving merge conflicts

Online and printed versions of a guide will be available.  The guide will outline these steps generally and the explanation of concepts will be a conversation between you and your group.  Along with the guide, we will have ideas for how you can explain certain concepts, and the initial repo ready for you to use with your group.

### Throughout

A whiteboard will be available for people to visit and write down topics/questions for a series of lightning talks at the end.

## Potential points of confusion

* not seeing any indication of password being typed at the command line
  * explain that this is normal, and is done to protect the password
* copy and paste in git-bash on windows doesn't work as expected
  * [ways to do it](http://stackoverflow.com/questions/2304372/how-do-you-copy-and-paste-into-git-bash)
* vi commit
  * we'll avoid this by teaching `commit -m`
* having to log in all the time from the command line
  * towards the end, you can help the learner [set up an ssh key](https://help.github.com/articles/generating-an-ssh-key/)
* thinking `commit` is the same as `push` 
 * we'll break up the two concepts by making a number of commits before pushing
