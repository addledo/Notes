**Terminal Commands**
- nproc - prints number of processing units available
- jobs - show background process
- realpath <file> - gives full path
- -   -s - don't expand symlinks
- -   -e - verifies file existence
- basename - gives name without path
- free - shows free memory
- top - shows running processes
- locate <rockyou.txt>
- xargs
- which / whereis
- ps - process status
- lsblk (list blocks) - drives
- lsusb -
- lsof - open files
- apropos - search commands
- sudo su - switch to root user
- tree [-d]
- tac - cat in reverse
- shutdown now - cooler than shutdown 0?

*Manipulation*
- | nl - adds line numbers
- head -n - display first n lines
- | tee <file> - outputs to terminal and file
- <cmd> 2>&1 | tee <file> - includes stderr
- ^foo^bar replaces foo with bar in last command
- tr - for replacing characters
- -   cat <file> | tr ' ' '\n' - replaces whitespaces with newlines
- echo -n - echoes empty string
- <some command> ``which zsh`` - adds zsh path
- find *.txt | awk '{print " " > $1}' - prints to all found *.txt files
- find -exec <command> - executes command on found files
- -   find -exec echo <command> - echos what will be done (use before running actual command)
- ls -1 - Lists each file on new line
- (zsh) repeat 100 {}
  
*apt*
- apt list --installed | grep (regex e.g. ^nmap)
- apt show {nmap}
- sudo apt full-upgrade (removes no longer needed dependencies)
  
- <command> & - puts process in background
- <command> & disown - separates from terminal
- pkill <process name> - kill process by name
  
**Terminal Shortcuts**
- Ctrl r - Search and edit previous commands
- Ctrl e - go to end
- Ctrl k - delete to end
- Ctrl w - delete last word
- Ctrl y - undo delete
  
**Linux Shortcuts**
- Ctrl alt F1..n - Virtual terminals?
  
**Learned**
- cd <no arguments> goes to home
- ; echo - use to add newline after command
- ls *.txt - lists all txt files
- Ctrl a - go to front of line
- Ctrl u - delete to start
- whomami
- REISUB - REBOOT EVEN IF SYSTEM UTTERLY BROKEN
- !! - last command
