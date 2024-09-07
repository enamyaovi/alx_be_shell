# ALX_BE_Shell Project
Hello and Welcome!

This ***README*** introduces the scripts I’ve created for Week 2 of the project. While most of the scripts cover basic Linux commands, working on them was an exciting experience for me.

I’ll be updating this README as I complete each task and script, simulating various commits and organizing the content like chapters in a book. Consider this the introduction.

I’ve also recorded parts of the assignment in video, so if I’m feeling confident, I may include links to those as well in future updates.

Thank you for stopping by, and welcome once again!

# CHAPTER_1: SWITCH USER SCRIPT
The script file 0-iam_betty contains an executable script for the linux command "su" or substitute user. This command allows you to change the current user to another system user.

According to the manual pages of su {man su}, when no user is specified it defaults to running an interactive shell as root (see GNU manual for more details). In this script, I specified the user as betty so that whenever that script is run, it prompts for betty's password. To simulate that this script works, I created a new user withthe {adduser} command and run the script. This user was called betty and had a password.

Since I was did this exercise in the ALx sandbox and I had access to the root user privileges, executing the script logs me in as betty without asking for a password. 

I plan on running the script as a different user to see how it behaves. Anyways that's all for now. Bye!

# CHAPTER 2: TELL SYSTEM USER SCRIPT
The script file 1-who_am_i contains an executable script for the Linux command whoami. This command is used to display the username of the current user. Since Linux systems support multiple users logged into different terminals simultaneously, you can see how this command works by switching users.

To simulate the script's functionality, I logged out from the root user and switched to one of the newly created users, such as betty. When running the script file as this user, the output returned is betty. For more information about the whoami command, you can read more here.
