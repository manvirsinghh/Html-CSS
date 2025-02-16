# Complete Linux Commands List

## 1. Basic Commands
| Command | Description |
|---------|------------|
| `pwd` | Show current working directory |
| `ls` | List files in a directory |
| `cd <directory>` | Change directory |
| `mkdir <dir>` | Create a new directory |
| `rmdir <dir>` | Remove empty directory |
| `rm <file>` | Remove file |
| `rm -r <dir>` | Remove directory and its contents |
| `cp <source> <destination>` | Copy file or directory |
| `mv <source> <destination>` | Move or rename file/directory |
| `touch <file>` | Create an empty file |
| `cat <file>` | Display file content |
| `nano <file>` | Open file in nano editor |
| `vi <file>` | Open file in vi editor |

## 2. File Permissions
| Command | Description |
|---------|------------|
| `ls -l` | Show file permissions |
| `chmod 777 <file>` | Change file permissions (rwx for all) |
| `chmod +x <file>` | Make file executable |
| `chown user:group <file>` | Change ownership of file |

## 3. Process Management
| Command | Description |
|---------|------------|
| `ps` | Show active processes |
| `top` | Show system resource usage |
| `htop` | Interactive process viewer (if installed) |
| `kill <PID>` | Terminate process by ID |
| `kill -9 <PID>` | Force terminate process |
| `pkill <name>` | Kill process by name |
| `jobs` | List background jobs |
| `bg` | Resume background job |
| `fg` | Bring job to foreground |

## 4. Disk Management
| Command | Description |
|---------|------------|
| `df -h` | Show disk space usage |
| `du -sh <dir>` | Show directory size |
| `mount <device> <dir>` | Mount device |
| `umount <device>` | Unmount device |
| `fsck <device>` | Check disk for errors |

## 5. User Management
| Command | Description |
|---------|------------|
| `whoami` | Show current user |
| `who` | Show logged-in users |
| `adduser <username>` | Add a new user |
| `deluser <username>` | Delete a user |
| `passwd <user>` | Change user password |
| `su <user>` | Switch user |
| `sudo <command>` | Run command as superuser |
| `groups` | Show user groups |

## 6. Networking Commands
| Command | Description |
|---------|------------|
| `ifconfig` | Show network interfaces (deprecated) |
| `ip a` | Show IP address info |
| `ping <host>` | Test network connectivity |
| `netstat -tulnp` | Show open ports |
| `curl <URL>` | Fetch data from URL |
| `wget <URL>` | Download file from URL |
| `scp <file> user@host:/path` | Secure copy file to remote host |
| `ssh user@host` | Connect to remote system via SSH |

## 7. Package Management
### For Debian-based (Ubuntu, Debian, etc.)
| Command | Description |
|---------|------------|
| `apt update` | Update package list |
| `apt upgrade` | Upgrade installed packages |
| `apt install <package>` | Install package |
| `apt remove <package>` | Remove package |
| `dpkg -i <package.deb>` | Install .deb package |


## 8. System Monitoring
| Command | Description |
|---------|------------|
| `uptime` | Show system uptime |
| `free -m` | Show memory usage |
| `vmstat` | Show system performance |
| `iostat` | Show CPU & disk usage |
| `lscpu` | Show CPU info |
| `lsblk` | Show disk partitions |

## 9. Searching and Finding Files
| Command | Description |
|---------|------------|
| `find /path -name "*.txt"` | Find files by name |
| `locate <file>` | Find file location |
| `grep "word" <file>` | Search for text in a file |
| `grep -r "word" <dir>` | Search recursively in a directory |

## 10. Archiving and Compression
| Command | Description |
|---------|------------|
| `tar -cvf archive.tar file1 file2` | Create tar archive |
| `tar -xvf archive.tar` | Extract tar archive |
| `tar -czvf archive.tar.gz dir` | Create compressed tar.gz |
| `tar -xzvf archive.tar.gz` | Extract tar.gz |
| `zip archive.zip file1 file2` | Create zip archive |
| `unzip archive.zip` | Extract zip file |

## 11. Crontab (Task Scheduling)
| Command | Description |
|---------|------------|
| `crontab -e` | Edit cron jobs |
| `crontab -l` | List cron jobs |
| `crontab -r` | Remove all cron jobs |

### Crontab Syntax:
```
* * * * * command-to-run
| | | | |
| | | | └── Day of the week (0-6, Sun=0)
| | | └──── Month (1-12)
| | └────── Day of the month (1-31)
| └──────── Hour (0-23)
└────────── Minute (0-59)
```
Example: Run script every day at 3 AM  
```
0 3 * * * /path/to/script.sh
```

## 12. Miscellaneous Commands
| Command | Description |
|---------|------------|
| `history` | Show command history |
| `alias ll='ls -la'` | Create alias |
| `unalias ll` | Remove alias |
| `echo "Hello"` | Print text to terminal |
| `date` | Show current date & time |
| `cal` | Show calendar |
| `clear` | Clear terminal screen |

---

This markdown file contains all the essential Linux commands categorized for easy reference! 🚀
