## Sudo 
`sudo` stands for superuser do" and is used in Unix-like operating systems to execute commands with elevated privileges. It allows users to perform administrative tasks by temporarily becoming the superuser or another authorized user.

![sudo](/PROJECT_1/images/sudo.png)

## Pwd
`pwd` (short for "print working directory") is a command that displays the current directory path in the terminal, helping users identify their current location within the file system.

![pwd](/PROJECT_1/images/pwd.png)

## Cd
`cd` (short for "change directory") is used to navigate the file system. It allows users to move from one directory to another. For example, cd /path/to/directory changes the current directory to the specified path.
![cd](/PROJECT_1/images/cd.png)

## Cd ..
`cd ..` is a specific usage of the cd command, which allows users to move up one directory level from their current location in the file system.

In the example below, running the command `cd ..` takes you back up one directory level. `cd ../..` takes you up two directory levels etc.

![cd_back](/PROJECT_1/images/cd_back.png)

## Ls
`ls` is a command used to list the contents of a directory. By default, it displays the files and directories in the current directory.

`ls -h` displays file sizes in a human-readable format, using units such as KB, MB, or GB, making it easier to understand the file sizes at a glance.

There are other options that can be specified e.g `ls -R`, which is used to list the contents of a directory recursively, displaying not only the files and directories in the specified directory but also those in its subdirectories.

`ls -a` lists all files and directories in the current directory, including hidden files and directories. Hidden files are those that start with a dot (e.g., .config).

![ls_human_readable](/PROJECT_1/images/ls_human_readable.png)

![ls _recursive](/PROJECT_1/images/ls_recursively.png)

## Cat
`cat` is a command used to display the contents of a text file in the terminal. It can also be used to concatenate and display the contents of multiple files.

![cat](/PROJECT_1/images/cat.png)

## Cp
`cp` (short for "copy") is used to copy files or directories from one location to another. It creates a duplicate of the specified file or directory in the destination location.

![cp](/PROJECT_1/images/cp_multiple.png).

## Mv
`mv` (short for "move") is used to rename files or move them from one location to another within the file system.

![mv](/PROJECT_1/images/mv.png).

## Mkdir
`mkdir` (short for "make directory") is used to create a new directory or folder in the current directory or at a specified path.

`mkdir -p` is an option for the mkdir command that allows you to create parent directories as needed. If the specified path includes directories that don't exist, it creates them.

![mkdir](/PROJECT_1/images/mkdir.png).

![mkdir](/PROJECT_1/images/mkdir_multiple.png).

## Rm
`rm` (short for "remove") is used to delete files or directories from the file system. Be cautious, as it does not move deleted items to a trash or recycle bin; they are permanently deleted.

![rm](/PROJECT_1/images/rm.png).


## Touch
`touch` is used to create an empty file or update the timestamp of an existing file. It's often used to create placeholder files or update file timestamps.

![touch](/PROJECT_1/images/touch.png).

## Locate
`locate` is a command used to quickly search for files and directories on the system. It relies on a pre-built database, making it faster than the find command for locating files.

![mv](/PROJECT_1/images/locate.png).

## Find
`find` is used to search for files and directories in a specified location. It offers more advanced search options, such as searching by file type, size, or modification time.


![mv](/PROJECT_1/images/find.png).

## Grep
`grep` (short for "Global Regular Expression Print") is a powerful text search tool used to search for specific patterns or text within files. It supports regular expressions for advanced searching.

![mv](/PROJECT_1/mages/grep.png).

## Df
`df` (short for "disk free") displays information about disk space usage on the system, including the amount of space used and available on various mounted filesystems.

![mv](/PROJECT_1/images/df.png).

## Df -h
`df -h` is an option for the df command that displays disk space information in a human-readable format, using units like GB or MB.

![mv](/PROJECT_1/images/df_options.png).

## Du -h
`du -h` is used to display the disk usage of files and directories in a human-readable format, showing the space each file or directory occupies.

![du](/PROJECT_1/images/du_human.png)

## Head
`head` displays the beginning lines of a text file in the terminal. By default, it shows the first ten lines, but you can specify a different number of lines to display.

![head](/PROJECT_1/images/head.png)

## Tail
`tail` displays the end lines of a text file in the terminal. By default, it shows the last ten lines, but you can specify a different number of lines to display.

![tail](/PROJECT_1/images/tail.png)

## Diff
`diff` is used to compare the content of two text files and display the differences between them line by line.

![diff](/PROJECT_1/images/diff.png)

## Tar
`tar` (short for "tape archive") is used to create and manipulate tar archives, which are commonly used for bundling and compressing files and directories.

![tar](/PROJECT_1/images/tar.png)

## Chown
`chown` (short for "change owner") is used to change the ownership of files and directories, allowing you to assign them to a different user or group.

![chown](/PROJECT_1/images/chown.png)

## Jobs
`jobs` displays a list of background jobs currently running in the terminal. It's useful when you have multiple processes running concurrently.

![jobs](/PROJECT_1/images/jobs.png)

## Chmod
`chmod` (short for "change mode") is used to change the permissions (read, write, execute) of files and directories, allowing or restricting access for users and groups.

![chmod](/PROJECT_1/images/chmod.png)

## Kill
`kill` is used to terminate processes on a Unix-like system. It sends a signal to the specified process, allowing you to stop it gracefully or forcefully.

![kill](/PROJECT_1/images/kill.png)

## Ping
`ping` is a network utility used to test network connectivity to a specific host or IP address by sending ICMP echo requests and receiving replies.

![ping](/PROJECT_1/images/ping.png)

## Wget
`wget` is a command-line tool for downloading files from the internet. It can retrieve files via HTTP, HTTPS, FTP, and more protocols.

![wget](/PROJECT_1/images/wget.png)

## Uname
`uname` displays system information, including the kernel version and system architecture, helping users identify the type of system they are using.

![uname](/PROJECT_1/images/uname.png)

## Top
`top` is a real-time system monitoring tool that provides information about system processes, resource usage, and system performance.

![top](/PROJECT_1/images/top.png)

## History
`history` displays a list of previously executed commands in the terminal, allowing users to view and rerun past commands.

![history](/PROJECT_1/images/history.png)

## Man
`man` (short for "manual") is used to display the manual pages (documentation) for various commands and system functions. It provides detailed information on how to use commands.

![man](/PROJECT_1/images/man.png)

## Zip
`zip` is used to compress files and directories into a Zip archive format, reducing file size for easier storage and sharing.

![zip](/PROJECT_1/images/zip.png)

## Unzip
`unzip` is used to extract files and directories from a Zip archive, restoring them to their original format.

![unzip](/PROJECT_1/images/unzip.png)

## Hostname
`hostname` displays the hostname of the system, which is the unique name used to identify a computer on a network.

![hostname](/PROJECT_1/images/hostname.png)

## Useradd
`useradd` is used to create new user accounts on a Unix-like system, allowing users to log in and use the system.

![duseradd](/PROJECT_1/images/useradd.png)

## Passwd
`passwd` is used to change a user's password on a Unix-like system. It provides a way for users to update their login credentials.

![passwd](/PROJECT_1/images/passwd.png)

## Userdel
`userdel` is used to delete user accounts from a Unix-like system, removing their access to the system.

![du](/PROJECT_1/images/userdel.png)

## Apt-get
`apt-get` is a package management command used in Debian-based Linux distributions to install, update, and remove software packages.


![du](/PROJECT_1/images/apt-get.png)

## Nano
`nano` is a simple and user-friendly text editor for the command line, making it easy for users to create and edit text files.

![nano](/PROJECT_1/images/nano.png)

## Vi
`vi` is a powerful and versatile text editor for the command line, known for its extensive features and keyboard shortcuts.

![vi](/PROJECT_1/images/vi.png)

## Alias
`alias` is used to create shortcuts or custom commands in the terminal, allowing users to define shorter or more convenient ways to run frequently used commands.

![alias](/PROJECT_1/images/alias.png)

## Unalias
`unalias` is used to remove previously defined aliases, returning the associated commands to their original state.

![unalias](/PROJECT_1/images/unalias.png)

## Su
`su` (short for "switch user") is used to switch to a different user account, often the superuser or another specified user, with appropriate privileges.

![su](/PROJECT_1/images/su.png)

## Htop
`htop` is an interactive system monitoring tool that provides a more detailed and user-friendly view of system processes and resource usage compared to top.

![htop](/PROJECT_1/images/htop.png)

## Ps
`ps` (short for "process status") is used to display information about the currently running processes on a Unix-like system.

![ps](/PROJECT_1/images/ps.png)