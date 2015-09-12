# 1.1 Think about time

#### Which time management and productivity ideas did you learn about?
Thanks to this research, I learnt about various strategies and techniques such as meditation, behavior improvements, start small, improved practicing, self-celebration, time-boxing… to improve my productivity by managing my time and mind in a better way. I feel like the idea behind most of those ressources is that you can hack yourself by doing some mind tricks that will change the approach you have on everyday’s situations. Since I’m already aware of the benefits of meditating for both my body and soul, creativity and productivity I gave more particular attention to the time-managing related links during this hour, and more particularly time-boxing.

#### What is "Time Boxing?" How can you use it in Phase 0?
Time boxing is a proven-effective way to work for our brain. Most of us are using it intuitively for a long time without even knowing the concept by its name. The idea of time boxing is to have a different approach on solving a problem or doing a task: it doesn’t properly consists in achieving the goal on the first time, but more to see what can be achieved in a certain (and delimited) amount of time. The example of “speed dating” is edifying. Time boxing is a very powerful strategy that can, must and will be used on purpose in a strategy in phase 0 by boxing tasks and organizing the work by times slots instead of tasks to complete.

#### How do you manage your time currently?
I consider my mind the most powerful tool to organize my work but I currently manage my time using a very basic mind dropping pen and paper technique: I drop everything that have to be done on my to-do list and then I order priorities. Because many people ask for my services in the office, I often have to re-prior tasks referring to the goals of my team and what have to be done as soon as possible to keep maintain a dynamic workflow. I have to confess that don’t actually use any time-management tools except the same old pen and a printed time table on my paper block. This approach also helps me keeping my mind clear and not bothering with to-do things when I’m focused on working. Even if it’s not directly related to time, I always try to listen to my body and to meditate or stretch on my free-time so I’m always ready to give the most out of myself when I have to, regardless of what time is it.

#### Is your current strategy working? If not, why not?
So far I’d say that my way is working. I’m just not sure I can call it a “strategy” but if it is, it sure can be improved! Even if I’m always on time when it comes to produce works and have no productivity problems on my projects, I think I am sometimes devoting too much energy to a task because I havent organized it well enough. Managing my time better, maybe with a time-boxed approach on some specific jobs could be an energy-saving thing. At least it would help me to prevent myself for entering the danger zone where I have to speed up and do crazy things to be right on time. The only reason why I think my current “strategy” may be not working good is because sometimes I still have to hurry to be in time referring to my personal engagements or my client’s delays and this can be very stressful.

#### Can/will you employ any of them? If so, how?
I know me, and I have learnt when I am the most productive in the past: early in the morning and in the night. I have also learnt that i’m not working at my best when I’m too much under time-pressure. Another thing is that I need some times not to be focused and giving myself some breaks when working on tedious or complex tasks, it’s amazing how the solution can pop-up from nowhere after a long break. So I will couple those few things I learnt about myself with a time-boxed strategy in order to have optimized work-sessions. On weekly basis, I’m going to organise my time table referring to both DBC week goals and personal, organizational constraints.

#### What is your overall plan for Phase 0 time management?
During the phase 0, I’m planning to use a strict pomodoro approach organized on a weekly
basis with a 6 step process for my time management:

1. Find out how much efforts the week challenges requires and try to monitor the amount of time I need to devote to each challenge (level of difficulty from 1 to 3).

2. Plan time-boxed working sessions on dedicated days of the week, taking care of having nothing around that can disturb me at the moment of the session. Starting to organize the sessions, for example I’d start a week with something that look hard to me so I have some extra time to think about it during the week before I commit it).

3. Make accurate estimations of time needed to achieve certain types of (complex) activities, trying to match activities based on same topics on the same days/sessions.

4. For each work session take time to: recap before you start and review once done, before committing.

5. Set the week time table according to the amount of time I have and what have to be done. Setting realistic mode to “on” in order to avoid sleepless nights! On the weekly time-table, allo extra time-slots for your personal extra-goals.

6. Keep in mind that my personal objective final objective beyond basic/completion objectives is improving. That’s why I’ll also manage some time to keep organized records of my practice so I can convince myself I’m actually getting better week after week.

# 1.2 The command line

#### What is a shell?
A shell is an interpreter. It’s a processor that execute commands in a certain language. The UNIX shell is both, an interpreter and a programming language.

#### What is "bash?"
The name bash is a programmer joke, and stands for bourne-again-shell because it is build on an improvement of 1977 Bourne shell command-line interpreter. Nowadays, bash is the default shell of OSX.

#### What was the most challenging for you in going through this material?
I feel the expected answer here must be the absence of GUI, but for I don't feel like this is a big deal with some training. The first time I understood that everything I could achieve with my mouse (and much more) could be achieved with commands and scripts I first felt so lost and stupid. Then, the most challenging was to deal with the idea of knowing nothing about my computer possibilities.

#### Were you able to successfully use all of the commands?
Yes, I was able to successfully use all of the commands.

#### In your opinion, what are the most important commands and arguments to know?
The most important is understand the structure of the command which is: command [options] arguments ; nextCommand

The list of commands that are listed below are the most important commands to do what a basic user is doing with GUI: know where you are, navigate to other folders, create, delete folders, works with datas.. Nevertheless, I think the power of unix is that it allows you to go further than the GUI, for example I love the `man` command to display the manual pages about some command when I need to learn about its options and possible arguments. I love using sublime thanks to `subl` too. Also, the `replace` or `grep` commands can may very powerful if combined with pipes `|` and appropriate `’regular expressions’` when it comes to do tedious tasks. I don't have much experience in this practice but after reading contents of the bonus command line course I'm eager try to use these. Also, I think some important concept is input `<` and output `>` because it can be very time saving for sorting/finding things that would have took ages with the GUI like making emails back-ups for example. Last but not least, it's not a command but a shortcut but usig tab in terminal is also very time saving.

#### Can you remember what each of the following does of the top of your head? Write what each does:
`pwd` print working directory (tells you where you are) returns: typing `pwd` in my working environement returns /Users/Paul

`ls` List informations about files. For example `ls [options] /Users` returns Paul and some hidden folders.

`mv` Move directory, used like `mv [options]… Source Destination/Directory`

`cd` Change directory, generally used with the target directory as argument like cd [options]… Directory…

`../`  Argument used as a symlink to parent’s directory of the current folder. For example, if I’m in /Users/Paul, typing `cd ../` will bring me into /Users, which is /Users/Paul parent directory.

`touch` Basicaly designer to modify a file timestamp it’s commonly used to a create a file, because when you use  `touch [options]… File…` if this file doesn’t exist, create it.

`mkdir` Make directory `mkdir [options]… folder…`

`less` Similar to cat but with less it is possible to scroll up and down in the file. It’s a joke because less is an improvement of the command more that was actually allowing less options for scrolling. In OSX, less is more!

`rmdir` Deleting an empty repertory, depends on the arguments. Used like `rmdir [options]… folder(s)…`

`rm` Remove files, deleter or unlink. Used as `rm [options]… file…`

`help` Displays a list of shell built-in commands. When used with one of these commands’s name as an argument like help someCommandFromTheList it will display useful informations about this command.

# 1.3 Git basics

#### Write an explanation of and compare git and GitHub to one another.
Git is a software that track changes allowing VCS (version control management). It’s an open source project. It helps developers to look back in time so see what happened on some specific parts of the development of the project. When working with three different people on the same project for example, git helps keeping one only project everyone collaborates on by sending files in and tracking changes instead of having three projects.. It’s a management control system. you First have to download it and then it lives locally on your computer. You generally use the command line and Git-ish commands to help you save and merge difference versions (branches) of your project..
On the other hand, gitHub is a platform, it means it does not lives on your computer. It’s the exact opposite of git in that sense because it lives remotely on the internet: it’s an online ‘hub’ for programmers to share code at the same time on common projects.
By the way, comparing git and gitHub is like comparing an Photo-Booth and Instagram. One is a program you run exclusively on the command line (git) and the other one is a service based on the git system, working online (on servers) at a world-wide level.

#### Explain what version control is and how GitHub helps with it.
As mentioned, Github and git are two slightly different things. Git is a piece of software running locally that help you handle version control. Once installed, you can create a new project directory with the command line and also tell Git to keep an history of changes made inside this directory. Version control (git) is keeping changes you make on the directory from steps to steps by taking snapshots every time you commit a change. This comes very handy when you are working with other people in a team because you can push and pull changes from/to other people machines. This way everybody is always up to date, working on the same versions of a file. Version control. Github came up with the idea of hosting online the common working directories you have to share with your coworkers, also known as repositories. This is how Github helps with version control, and even it nowadays, Github provides tons of incredible futures like social media network for the IT community, website dynamic creation and more, it’s mainly a repository host. Some very important thing to understand is that, default repositories are public, making Github more than a simple web server hosting ‘repos’. Github is a collaborative tool and place where developers can collaborate freely in order to create better software, together.

#### Why do developers use version control (git)?
Developers use git because it facilitates tracking (collaborative) changes to files, making possible and easy the (collaborative) history tracking of all the files that compose the project (design, code, license…).
Thanks to merging options of version control systems, developers can merge changes, at the same time, and this with precision and ease. It’s also fast modern and light weight and provides a nice working experience for any kind of knowledge worker that need to keep track of what has been done.
In fact, in the field of web developemment, when a developer is trying to achieve a piece of code, he can sometimes have to try several different approaches from a precise step he achieved in the past. So developers will have to try different approaches, creating several different files. Once they figure out the solution they will commit it on a branch of the project so it can be integrated later in the master project branch of the project if it is an improvement.

#### What is a commit?
A commit is a like an official “saving” of a code file. Every time, a small task has been done or some improvement has been achieved, a developer is committing the related code to his branch. When working on software, the master branch is always expected to work perfectly, even at a lower and well-tested version of the project, the master must always be ready to be run, and thats the reason why when you’re working on improvements you’re not directly committing to the master branch.
Considering a commit is usually useful in the context of collaborating with others developers, it’s important to understand that it is not only a piece of code, but also a nicely written text message explaining, what has been added to the project, why and how it has been added, and if needed, the side-effects it can have on the project.

# 1.4 Forking and Cloning

#### How to create a repo:
Go on https://github.com/  and register an account. Then log in.
On the landing page, in the main menu on the top right corner, click the “+” button, then create new Repository. This will bring you to the repository creation page. Here you will follow the procedure by filling the form, naming your repository and adding a readme and a license if you need to. Then, click the green “Create repository” button in order to create your repository on Github servers.

#### How to fork a repo:
Click the "Fork" button at the top right of the repository page. This will make a copy of the repository into your personal GitHub account. The repo is now forked.

#### How to clone a repo:
Right now your repository exists on GitHub, but in order to add or edit files using your text editor, you need it to exist on your computer. In git terms, this is called cloning a repository locally.  A "local repository" is the copy on your computer. A "remote repository" is one on another server, i.e. on GitHub, or on another person's computer. You can now use the command line in order to clone repositories: Clone mean you'll bring the repository to your computer. To proceed: copy the url below the HTTPS clone URL panel. Then, switch to the terminal in order to use the command line. Once in the in the terminal check where you are with pwd. Make sure you are in the correct directory, like your Desktop or an appropriate folder and use the command:  `git clone URL_THAT_YOU_COPIED`.

#### Forking instead of creating new repository
Forking is allowing an user to access to the actual version of a file, which mean the whole contents of the project located in the forked branch. It’s a both a good habit to take and a safer way than copying and pasting directories and lines of codes from an environment to another. In addition, the repository already have the appropriate naming conventions of the project, you don't have to do anything but making changes! The main struggles I faced when setting up git and Github was ensuring myself I was cloning the forked repository from my Github page and not from the one from the original DBC one. I learnt that working this way is very safe in terms of saving files and keeping track of these. Also, this experience makes me more eager to improve my code skills in order to collaborate legitimaly with other developers, forking repos on interesting gitHub projects I could improve...