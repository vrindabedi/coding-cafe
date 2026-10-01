# Lab 1 Answers

## Where am I?
1. pwd stands for 'print working directory' which means the folder I'm in right now or my current user directory path (/home/vrinda)
2. ls -a stands for list all which means it lists all of the files, even the hidden ones starting with a dot like .bashrc & .profile. Whereas ls is just plain list which does not show the hidden files.
3. ls -l stands for long listing. (drwxr-xr-x 4 vrinda vrinda 4096 Aug 27 10:41 coding cafe)
	 d is for directory rwx for read write and execute. rx means 'Vrinda' (The people with access to this) can read and execute but not change.
	4 means the path ways directing to that folder
	4096 is the file size of the folder
	And then is the last modification date and time
 ##Changed
## Build the Folder
4. It works because coding-cafe/week02 is a relative path. It starts from looksing from my current folder (the one I am in) instead of the absolute root system.

## Move, Copy, Rename, Delete
5. mv did two different jobs which were to rename and move the file.

## Where does the Shell find things?
6. Currently there are 21 folders including python 3.14 in my PATH
7. python3 lives in /usr/bin/python3
8. It doesn't have to necessarily be the same because there are different directories depending on the interface being used.
9. The Shell searched every folder listed in the PATH but found no such executable file hence "command not found" and offered to autocorrect the commnand "Did you mean python3?"

## A box of your own
10. .venv did not appear with the plain l command because it's a file starting with . as in '.venv'  which means it is considered as a ' hidden file'
11. Everything remains same except we get a (.venv)before the PATH in the interface to show that we are in our created virtual environment.
12. Yes it is different since it is now in my coding-cafe folder. Activate basically changed the path of the python3 from global to local.
13. The first time pip list shows the few packages installed in my virtual environment. When we write pip install requests it basically  installs a library called ' requests in the virtual environment and then pip list lists out the packages that have now been installed.
14. After de-activating python3 again is back into usr/bin/python3 (the original PATH)

## Read a manual
15. ls -h basically works like ls, just lists out all the directories. But when paired with -l as in ls -lh it gives the file sizes along with the date and time at which they were last modified.
16. Ctrl + C interrupts the current line (shows 'KeyboardInterrupt') and erases whatever was written in that line and moves to a fresh line >>>
	Ctrl + D sends an 'End of File' symbol and completely closes the python shell and exits back out to the regular terminal ($)
