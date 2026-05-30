# Linux Basics Day 2

## pwd
Shows where I am in the file system right now.
Example: pwd
Output: /Users/nabinair

## ls
Lists files and folders in current location.
Example: ls
With flags: ls -la shows hidden files too and adds details like permissions and owner.

## cd
Change directory. Moves you into a folder.
Examples:
cd Documents goes into Documents
cd .. goes up one level
cd ~ jumps to home folder

## mkdir
Creates a new folder.
Example: mkdir practice

## touch
Creates an empty file.
Example: touch testfile.txt

## cat
Shows what is inside a file.
Example: cat testfile.txt

## echo and redirects
echo prints text on screen.
Example: echo "hello"

> overwrites a file with new content. Old content is gone.
Example: echo "hi" > test.txt

>> adds to the end of a file without deleting old content.
Example: echo "more text" >> test.txt

In security, log files use >> because you never want to erase old logs.

## grep
Searches for text inside a file.
Example: grep "security" testfile.txt
Shows only lines that contain the word "security".

Useful flags:
grep -i  searches without caring about uppercase or lowercase
grep -n  shows line numbers
grep -r  searches inside all files in a folder

In security work this is used to search through huge log files for things like failed logins.

