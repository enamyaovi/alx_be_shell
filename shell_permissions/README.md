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

# CHAPTER 3: CREATE NEW EMPTY FILE_HELLO
The script file 4-empty contains an executable script for the Linux command touch. This script creates a new file named hello. While it might seem a bit unnecessary to create a file with a simple name like hello, it's a handy way to quickly generate empty files for various purposes.

Fun Fact: The touch command is not just for creating empty files! It can also be used to update the timestamp of existing files, making it useful for various file management tasks.

# CHAPTER 4: SET FILE PERMISSIONS FOR OWNER of HELLO
Remember the hello file I created earlier that I mentioned might not be necessary? Well, I wrote a new script to update its permissions for the owner using octal mode. Why octal mode? Because it’s faster and more convenient!

I’ve read that some people find octal mode harder to grasp, but thanks to my mentor Nehemiah, I found it quite manageable. I’m planning to learn more about the symbolic mode for changing file permissions in the future.

On a side note, I discovered that setting file permissions on the Windows command line is far more complicated. Now I understand why developers prefer Linux/Unix systems! I almost lost my mind trying to figure out the Windows equivalent of the chmod command. I’ll tackle that another time. For now, that’s all—bye and thanks!

# CHAPTER 6: SET MULTIPLE PERMISSIONS
This script will set multiple permissions for different user groups: the file owner, the owner's group, and all other users. The file in question is hello, the same file created in the "4-empty" script. I now feel confident with using octal notation for setting permissions on files, directories, and libraries. It's satisfying to realize I’ve learned something new since yesterday.

# CHAPTER 7: JOHN-DOE WHO??
Who is John Doe? Well, he's your typical, everyday figure—a placeholder name used for an unknown or anonymous person. The name "John Doe" has been used in legal contexts dating back to the 13th century in England, where it was applied to anonymous or hypothetical parties in court cases. Over time, it became synonymous with a generic, unidentified individual.

Now, back to business. This script will set the permissions for the hello file to a specific value. Why this value? Honestly, I didn’t question it. My goal this week is to pass my project, so I’m following instructions. No, I don’t subscribe to a hive mind. Running the script will set the file permissions to -rwxr-x-wx for the hello file.

That's all for now! Thanks for reading, and see you in the next project. 👋
