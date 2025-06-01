# CSCI440 Useful Links

## Git

* [Git](https://git-scm.com/) - Free and open source distributed version control system

* [GitHub](https://github.com) - Source code hosting service for software projects using Git that provides distributed version control, access control, bug tracking, software feature requests, task management, continuous integration, and wikis. (subsidiary of Microsoft)
  * [GitHub Student Developer Pack](https://education.github.com/pack) - Offers free access to tools and services used by professional developers, including Travis CI
  * [GitHub's SSH instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh) - Connecting with SSH is secure and can simplify your git workflow. I find their sections on [Generating a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and [Adding a new SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) to be particularly useful.
  * [GitHub's git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)

* [GitLab](https://gitlab.com) - GitLab is an open source end-to-end software development platform with built-in version control, issue tracking, code review, CI/CD, and more. Self-host GitLab on your own servers, in a container, or on a cloud provider.
  * [GitLab's git cheat sheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)

* [BitBucket](https://bitbucket.org/) - Git-based source code hosting service for software development projects (owned by Atlassian)
  * [BitBucket's git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)

* [Git Basics Video](https://www.youtube.com/watch?v=0JgyAJMvZlY&feature=youtu.be) - Basic tutorial on using git for version control I recorded Spring 2020

* [Learn Git Branching](https://learngitbranching.js.org/) - Excellent web tutorial working through a variety of use cases for git including using branches.

* [freeCodeCamp Git Cheat Sheet](https://www.freecodecamp.org/news/git-cheat-sheet-helpful-git-commands-with-examples/#heading-reverting-changes-in-git) - An extensive guide to Git commands, with explanations and examples.

## Development Environment

* [Ubuntu](http://www.ubuntu.com/) - Linux distribution based on Debian and composed mostly of free and open-source software. It is recommended that you use Ubuntu 22.04 LTS or 24.04 LTS
  * Note: if you use Ubuntu 24.04 LTS, you will NOT be able to run the command, `apt-get source linux-image-$(uname -r)` to download the Linux kernel source code; however, this command should not be necessary anymore, so it should not impact your ability to complete any assignments.

* [Google Cloud Console](https://console.cloud.google.com/)
  * We will use Compute Engine to launch a virtual machine (VM). Using a VM is recommended for Assignment 1, since this assignment has you modifying privileged code and you could potentially corrupt your native system if you are not using a VM.
  * Other assignments can be completed in another UNIX environment (such as [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) or [ecc-linux](https://www.ecst.csuchico.edu/docs/)), but you may choose to complete all assignments in a Compute Engine VM instance.

* [Dev Docs](http://devdocs.io/) - Searchable documentation of many popular languages. Includes C documentation, which is what we'll be using primarily in this course. But great resource for all of you long term.
