# Linux Basic Commands Lab

Practical Linux command examples for navigation, file management, permissions and process control.

## Navigation

- `pwd` → show current directory
- `ls` → list files and folders
- `ls -la` → detailed list including hidden files
- `cd folder_name` → enter a directory
- `cd ..` → go back one level

## File Management

- `touch file.txt` → create empty file
- `mkdir test_folder` → create directory
- `cp file.txt backup.txt` → copy file
- `mv file.txt newname.txt` → move or rename file
- `rm file.txt` → remove file
- `rm -r test_folder` → remove directory recursively

## Viewing Files

- `cat file.txt` → display file content
- `less file.txt` → scroll through file
- `head file.txt` → first lines of file
- `tail file.txt` → last lines of file

## Permissions

- `ls -l` → show permissions
- `chmod +x script.sh` → make file executable
- `chmod 644 file.txt` → standard file permissions
- `chown user:user file.txt` → change owner

## Process Management

- `ps aux` → list running processes
- `top` → live process monitor
- `kill PID` → terminate process
- `pkill process_name` → kill by name

## Notes

All commands tested in Linux environments for hands-on practice.
