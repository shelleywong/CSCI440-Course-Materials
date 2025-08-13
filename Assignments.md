# CSCI440 Assignments

There will be at least 6 assignments due at approximately 2 week intervals starting the second week of the semester. There will also be an inquiry based final project due at the end of the semester in lieu of a final exam.

For the first assignment, you will need to use a Linux virtual machine. All assignments must be able to work in a UNIX-based environment such as Linux – programs submitted to INGInious will be tested using the GNU compiler (gcc, a standard compiler for many modern Unix-like operating systems).

## Assignment Instructions

Instructions for each of the assignments can be found at the repos linked below, inside of the [CSUChico-CSCI340 GitHub organization](https://github.com/CSUChico-CSCI340). These repos also contain handouts/code that you can use as a starting point.

* **Assignment 1: Writing a Kernel Module**
  * [CSCI440-KernelHacking](https://github.com/CSUChico-CSCI340/CSCI440-KernelHacking)
  * Goal: For you to become more familiar with how kernel modules are written and aspects of the Linux operating system using these modules
* **Assignment 2: Writing Your Own UNIX Shell**
  * [CSCI440-Shell-Assignment](https://github.com/CSUChico-CSCI340/CSCI440-Shell-Assignment)
  * Goal: For you to get practice with exceptional control flow.
* **Assignment 3: Writing a Scheduler**
  * [CSCI440-Scheduler](https://github.com/CSUChico-CSCI340/CSCI440-Scheduler)
  * Goal: For you gain insight into how schedulers work on the system.
* **Assignment 4: Virtual Paging**
  * [CSCI440-Virtual-Paging-Assigment](https://github.com/CSUChico-CSCI340/CSCI440-Virtual-Paging-Assignment)
  * Goal: Implement a paging strategy that maximizes the performance of the memory access in a set of predefined programs.
* **Assignment 5: DNS Resolver (Threads Only, Mutex/Semaphores)**
  * [CSCI440-DNS-Name-Resolution-Engine](https://github.com/CSUChico-CSCI340/CSCI440-DNS-Name-Resolution-Engine)
  * Goal: Develop a multi-threaded application that resolves domain names to IP addresses. Your application should synchronize access to shared resources and avoid deadlock, using mutexes and/or semaphores to meet this requirement.
* **Assignment 6: DNS Resolver (IPC)**
  * [CSCI440-DNS-Name-Resolution-Engine-IPC](https://github.com/CSUChico-CSCI340/CSCI440-DNS-Name-Resolution-Engine-IPC)
  * Goal: Develop a multi-process application that resolves domain names to IP addresses, using shared memory (a form of inter-process communication (IPC))
* **Inquiry Based Final Project**
  * [final-project](https://github.com/CSUChico-CSCI340/final-project)
  * Goal: Answer a question about a topic related to Operating Systems, devise a way to test and/or gain understanding about the question through a hands-on implementation of the concept, and write up a document with your findings.

> Note: It is recommended that you do NOT clone these repos and copy them into your CSCI440 repo, so you can avoid the issue of having a git repo inside of another git repo.

It is recommended that you:
  - Go to the assignment repo and click on the green Code button
  - Make sure you are on the Local tab and select the Download ZIP option
  - Save the file and then unzip the .zip file (to extract, can usually double click, press and hold, or right click on the file and Extract All, or use the `unzip` UNIX command)
  - If you haven't already, move the contents of the zipped folder so that is inside your CSCI440 repo (the .zip file can be discarded)
  - Now, if you run the `git status` command inside of your CSCI440 repo, you should see that the assignment directory has been added to your repo, and you should be able to use the git add/commit/push commands to save code inside this new subdirectory.
