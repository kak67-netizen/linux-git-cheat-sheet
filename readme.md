# Linux and Git Command Cheat Sheet

This cheat sheet contains common commands used in Linux and Git.

## 1. `pwd`

**Description:** Displays the full path of the current working directory.

**Syntax:** `pwd`

**Example:** Running `pwd` may display `/home/kyla/linux-git-cheat-sheet`.
## 2. `ls`

**Description:** Lists files and directories in the current directory.

**Syntax:** `ls [options]`

**Example:** `ls -la` displays all files, including hidden files, in a detailed format.
## 3. `cd`

**Description:** Changes the current working directory.

**Syntax:** `cd <directory>`

**Example:** `cd /home/kyla/linux-git-cheat-sheet` moves into that directory.
## 4. `mkdir`

**Description:** Creates a new, empty directory.

**Syntax:** `mkdir <directory>`

**Example:** `mkdir notes` creates a new folder called notes in the current directory.
## 5. `rm`

**Description:** Deletes files, or directories when used with the -r flag.

**Syntax:** `rm <file>` or `rm -r <directory>`

**Example:** `rm -r old-notes` deletes the old-notes directory and everything inside it.
## 6. `cp`

**Description:** Copies a file or directory from one location to another.

**Syntax:** `cp <source> <destination>`

**Example:** `cp readme.md backup.md` creates a copy of readme.md named backup.md.
## 7. `mv`

**Description:** Moves or renames a file or directory.

**Syntax:** `mv <source> <destination>`

**Example:** `mv notes.txt archive/notes.txt` moves notes.txt into the archive folder.
## 8. `cat`

**Description:** Prints the contents of a file to the terminal.

**Syntax:** `cat <file>`

**Example:** `cat readme.md` displays the full contents of readme.md.
## 9. `touch`

**Description:** Creates a new, empty file, or updates the timestamp of an existing one.

**Syntax:** `touch <file>`

**Example:** `touch notes.txt` creates an empty file called notes.txt.
## 10. `chmod`

**Description:** Changes the read, write, and execute permissions on a file or directory.

**Syntax:** `chmod <permissions> <file>`

**Example:** `chmod 755 script.sh` gives the owner full access and read/execute access to everyone else.
## 11. `grep`

**Description:** Searches text for lines matching a given pattern.

**Syntax:** `grep "pattern" <file>`

**Example:** `grep "error" log.txt` prints every line in log.txt containing the word error.
## 12. `man`

**Description:** Opens the manual page for a command, showing its usage and options.

**Syntax:** `man <command>`

**Example:** `man ls` opens the manual page explaining all options for the ls command.
## 13. `git status`

**Description:** Shows the current branch and which files are staged, unstaged, or untracked.

**Syntax:** `git status`

**Example:** Running `git status` after editing readme.md shows it listed as modified.
## 14. `git log`

**Description:** Displays the commit history for the current branch.

**Syntax:** `git log`

**Example:** `git log --oneline` shows a condensed, one-line summary of each commit.
