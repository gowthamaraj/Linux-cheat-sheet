# **Linux Cheat Sheet**
---
### Linux Filesystem Hierarchy
```
/ ---> root 
/root ---> home directory for root user
/home ---> home directory for other users
/usr ---> by default, softwares are installed here (UNIX sharable resources)
/bin ---> commands used by all users
/sbin ---> commands used by root users
/var ---> variable data/ logs
```

### Files and Directories
 - date 
 - cal
 - uptime
 - whoami
 - users
 - who
 - ls / ls -al / ll / ls -ltr / ls -ld <dirname>
 - pwd
 - cat <filename>
 - less <filename> ---> ENTER / e / y
 - more <filename>
 - head <filename> -n 5
 - tail <filename> -n 5
 - touch <filename>
 - cat > <filename> / cat >> <filename>
 - mkdir <dirname> / mkdir -p <dirname1/dirname2>
 - rm -rf <dirname>
 - rmdir <dirname>

### Managing files and directories
 - cp <source> <dest.> / cp -r dir1 dir2 
 - mv <source> <dest.>
 - cd / cd ..
 - find / -(user/name/group) (filename/username/groupname)
 - diff file1 file2
 - file <filename>
 - grep <regex> <filename> / grep -i <regex> <filename>

### User management 
 - useradd <option> <username>
 - usermod -G <groupname> <username>
 - chmod u+r,g-r,o+rx <filename/dirname>
 - chmod 777 <filename/dirname>
 - sudo chown user:group <filename>
 
### System management
 - history
 - free / free -m 
 - cat /proc/meminfo
 - cat /proc/cpuinfo
 - uname -a
 - which ls
 - df / df -m