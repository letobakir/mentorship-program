# Linux commands
`cd <folder>`  - opening dir

`cd ..` - going back 

`ls` - list of the directories

`ls -la` - list of the directories and files

`pwd` - position where we are

`hostname -I` - IP address

`touch <ime fajla>` - creating a file

`mkdir <ime dir>` - creating a dir

`chmod` - adding permissions to the file

`readlink -f <file/dir>` - file/dir path

`rm -rf` - deleting dir 

`./<name of the script>` - starting a script

`bash <name of the script>` - starting a script

`cat <ime fajla>` - opening .txt and .md files

`vi <ime fajla>` - creating and opening of the file

`sudo` - root user

`chmod -R 640 `.. changes the file permissions recursively for all files and directories`

`sudo su` - always be in root mode

`exit` - exit root mode

`date` - print date

`sudo apt update` - update 

`sudo apt upgrade` - upgrade

`mv <name of the file> <new name>` - rename the file

`mv <name of the file> <path where to move a file>` - move a file

`cp <name of the file> <new name of the file>` - copy

`cp <name of the file> <path where to copy a file>` - copy a file

`find /path/to/the/directory -type f -exec chmod 640 {} \;`

- `find` - to find files/directories within specifyed directory
- `-type f` - searching for files
- `-type d` - searching for directories
- `-exec` - executing commands on found files
- `chmod 640` - assigning permissions 6-4-0 to the found files
- `{}` - represents every discovered file.
- `\;` indicates the end of the command for each file.
  

`.bashrc` - When you open a terminal or start a new session in Bash, the ***.bashrc*** file is read and executed. This file is used to set up your environment.

`cronjob` - a file containing the schedule of various cron entries that should be run at specified times.

```bash
4 - r

2 - w

1 - x

Owner|Group|Others
```

## Commands within vi
`I` - by typing I in vi you can write in file 
`esc + :wq` - saving a file
`esc + :q!` - quiting and not saving a file

