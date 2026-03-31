# Linux Commands
- cd = Moves you to the root directory instandly
- --help = Think of it as a 'Emergency Button' you press when you are stuck or can't remeber which parameter to use
- -a = All"—displays hidden files (those starting with a dot)
- mkdir = Make Directory: creates a new, empty folder in your current location.
- *.png/jpg/pdf = If you want  to copy mutliple file than you should use (*.png/jpg)this Parenthesis
- cp = This command is for copying anything
- ~/Desktop/ = This you type when you want to check a folder or enter a Folder
- cp -r = The (-r) here means recurse which means you are also copying whatever is inside the folder not only the Folder
- cp -r /Desktop/See_me_now ~/Documents/ = So here the (Desktop) is the source from where you are copying the file and (See_me_now) is the file name which is inside the Source and than (Documents) is the Destination where you are sending your file to.
- mv =  Moving and Renaming Files, Directories
- cat[filename] = # cat [filename]
- more[filename] = Pauses text page by page.Use for long files so they don't scroll away.
- nano = Nano is the tool you use inside the terminal. Nano is a simple, beginner-friendly command-line text editor. It is most famous on Linux, but it is also available in PowerShell.
- Get-Alias = Alias is a great way of getting to know about the Shortcut Commands , which can be confusing when you change from one operating system to another
- echo = echo is an alias for Write-Output. It is used to display text in the console or send text into files.
- uniq = Deletes all the duplicate names, leaving only one of each.
- ./ = As we discussed earlier, if a filename starts with a dash (like -file01), the terminal thinks the dash is a command option (like -p or -a).
When you use ./-file01, you are changing the "name" the computer sees.
• The Problem: cat -file01 → Computer thinks you're asking cat to use a "setting" named f.
• The Fix: cat ./-file01 → Computer sees the path first, realizes it’s a file, and opens it correctly.
- file ./ = To know what kind of file it is
- passwd (Put your username here) = For changing password in Linux
- sudo passwd - e (than the username here) = for let others change their password
- sudo useradd [name] = To create an account in Linux
- sudo userdel [name] = for Deleting an account
- 2>/dev/null = in the real world, if you are looking for a log file on a server with 1000000 files, your terminal will be flooded with”Permission denied” because you don’t have access to the private folders of other users . Without this trick, finding the 
- grep = grep searches for a specific string of text (a "pattern") inside a file or multiple files. It’s like using Ctrl + F, but much faster and more powerful.
Basic Search: grep millionth data.txt(Finds every line in data.txt that contains the word "millionth")
- icalcsC:TestLock /deny fortn:F= This is for an user to not give access to a folder only the admin has the right to Access.
