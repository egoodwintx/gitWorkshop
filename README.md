# The Plan

## Set-up

When learners enter, there is a set up table to get them setup.  Most of us will help out with the initial wave of learners checking and helping with set up.

### Set-up checklist
- [ ] GitHub account?
  * Remind learner to verify email
- [ ] https://git-scm.com/downloads
  * git-bash for Windows
  * [avoid Xcode for Macs](http://blog.bobbyallen.me/2014/03/07/how-to-install-git-without-having-to-install-xcode-on-macosx/)
  * Verify by doing `git --version`
- [ ] [git configs set](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup#Your-Identity)**
  * user.name
  * user.email
  ```bash
  git config --global user.name "your name"
  git config --global user.email "youremail@youremail.com"
  ```
* no need to set up ssh keys at the beginning
  * If there's time, we may help with this at the end of the workshop.

** Notice that we are leaving [`core.editor`](https://help.github.com/articles/associating-text-editors-with-git/) [option](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup#Your-Editor) out.  We anticipate running into questions if the commit window with VI comes up.  However, this is unlikely and may only happen late in the workshop.  Since not everybody will have a text editor, we don't want to preemptively go on a tangent to set this.

## Curriculum

As traffic coming in slows down, more and more of us will settle down with a group of learners (up to 5) through:

### Collaborating together on your groups' git repo
  * ~ 0.5 hrs - 1.5 hrs
  * a repo of recipes
    * Fork this -- link to come -- and then add your group members' gh usernames

#### Learners with no cmdline experience
*will do this within the GitHub website*

**Concepts**

1. Branching
1. Commiting, and writing commit messages
1. PRs
1. Review, diffing and merging
1. master
1. Issues

#### Learners with come cmdline experience
*will do this in the commandline*

**Concepts**
All of the above plus

1. local vs. remote
1. cloning
1. git checkout/branching locally
1. staging files/git add
1. pushing
1. pulling

### Starting a fresh repo
  * ~ 0.5 hrs - 1.5 hrs

#### Learners with no cmdline experience
will be introduced to the commandline

**Commandline concepts**

1. what is it?
1. paths
1. commands
  * `ls`
  * `mkdir`
  * `pwd`
  * `cd`

**Git concepts**

1. `git init`
1. local vs remote
1. `git push`

#### Learners with come cmdline experience
*will do this in the commandline*

**Concepts**
All of the above

### Practicing collaboration with each other's repos

1. forking
1. how to add collaborators
1. github organizations
1. merge conflicts

Online and printed versions of the guide will be available.  The guide will outline these steps generally and the explanation of concepts will be a conversation between you and your group.  Along with the guide, we will have ideas for how you can explain certain concepts, and the initial repo ready for you to fork and use with your group.

### Throughout

A whiteboard will be available for people to visit and write down topics/questions for a series of lightning talks, if there's time and interest.

## Potential snags
* git-bash on windows
  * [copy and paste is sneaky](http://stackoverflow.com/questions/2304372/how-do-you-copy-and-paste-into-git-bash)
* vi commit
  * potentially confusing to beginners...
