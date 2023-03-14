# Title: Directory Backup
### This is a simple shell script that automates the process of creating a backup of a directory

## How to use:
1. To use this script, save it as a text file with a .sh extension (e.g. backup_script.sh). 
2. Then, navigate to the directory where the script is saved and run the following command in your terminal:bash backup_script.sh
3. This will execute the script and create a compressed backup file of the specified directory. You can modify the DIR_TO_BACKUP and BACKUP_FILE_NAME variables to fit your needs. Additionally, you can add more commands to the script to further automate the backup process, such as copying the backup file to a remote server or scheduling the backup to run at specific intervals using a tool like cron.

## Purpose:
I wanted to practice using shell scripting that would automate something useful in my life and it was fun way to learn shell scripting.

## What is shell script?
A shell script is a script written in a shell programming language that runs on a command-line interface (CLI) or terminal. A shell is a program that acts as an intermediary between a user and the operating system, allowing users to interact with the operating system through a command-line interface.

Shell scripts are written to automate tasks and processes that would otherwise need to be manually performed by a user. Shell scripts can be used to perform a wide variety of tasks, such as system administration, file management, and data processing. They can also be used to create more complex scripts that combine multiple commands and operations.

Some common shell scripting languages include Bash (Bourne-Again SHell), Zsh (Z shell), Ksh (Korn shell), and Fish (Friendly Interactive SHell). These shells provide a range of programming features, such as variables, loops, and functions, to allow users to write more complex and powerful scripts.

Shell scripts can be executed in a terminal by running the script file, or by invoking the shell and passing the script as a command-line argument. Additionally, shell scripts can be scheduled to run automatically using a tool like cron.

## Shell script vs Bash script
The main difference between shell scripts and Bash scripts is that shell scripts can be written in any shell programming language, while Bash scripts are specific to the Bash programming language. Bash scripts can take advantage of the specific features and syntax of the Bash programming language, which may differ from other shell programming languages. For example, Bash has a number of features and built-in commands that are not available in other shell languages.

In summary, shell scripts are a more general category of scripts that can be written in various shell programming languages, while Bash scripts are shell scripts written specifically in the Bash programming language.

## Things I learned:
1. Shell scripting: By creating a shell script to automate the process of creating a directory backup, you may have gained a deeper understanding of shell scripting concepts, such as variables, loops, conditional statements, and functions.
2. File system management: By working with directories and files in your project, you may have learned more about how file systems work, including how to navigate directories, create and delete files and directories, and manage permissions and ownership.
3. Automation: By automating the backup process, you may have discovered the benefits of automation, including saving time and reducing the likelihood of errors, and gained experience in implementing automation solutions.
4. Error handling: By anticipating and handling potential errors in your script, you may have learned more about error handling techniques, such as using try-catch blocks, exit codes, and error messages, and gained experience in debugging code.

## Things I would improve:
1. Security: Ensure that your script does not expose sensitive information, such as login credentials, and that it follows security best practices, such as limiting access permissions and validating user input.
2. Usability: Consider making your script more user-friendly by providing clear instructions, using meaningful variable names, and offering options for customization, such as specifying the backup destination or excluding certain files or directories.
3. Error handling: Review your error handling approach and ensure that your script handles potential errors effectively, such as by logging errors or providing helpful error messages that help users understand what went wrong and how to fix it.

