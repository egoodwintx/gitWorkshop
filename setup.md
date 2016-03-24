## Set-up

When learners enter, there is a set up table to get them setup.  A few of us will help out with the initial wave of learners checking in and helping with set up.

### Set-up checklist

- [ ] GitHub account
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
- [ ] [Atom](https://atom.io/) if no editor

Our goal here is this get set up quickly and with enough to hit the ground running.  We want to keep the focus on GitHub and git as much as possible in the beginning.  For example, we are leaving out [setting up ssh keys](https://help.github.com/articles/generating-an-ssh-key/) with GitHub.  If there's time, we should help with this at the end of the workshop.

** Also, notice that we are leaving [`core.editor`](https://help.github.com/articles/associating-text-editors-with-git/) [option](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup#Your-Editor) out.  We anticipate running into questions if the commit window with VI comes up.  However, this is unlikely to happen because we'll be teaching `git commit -m`.  Since not everybody will have a text editor, we don't want to prematurely go on a tangent to set this.
