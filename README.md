# Linux Assignment

## SECTION 1 – Write the purpose and an example usage for each command.

1. `pwd` - Shows current directory  
2. `ls` - Shows current floder's files or floder  
3. `cd` - Used to switch the floder  
4. `mkdir` - Used to create floder  
5. `rm -rf` - Used to Delete the floder  
6. `ps -ef` - Shows the all running process detials  
7. `top` - Shows CPU Usages and running processes  
8. `df -h` - Check the disk storage usage of the server  
9. `history` - Shows history  
10. `uptime` - Shows duration of system using  


## SECTION 2 – Write the Linux command for the following tasks.

1. Create a directory called project-files  
```
mkdir project-files
```

2. Navigate into the project-files directory  
```
cd project-files
```

3. Create a file called notes.txt using vi  
```
vi notes.txt
```

4. Display the contents of notes.txt  
```
cat notes.txt
```

5. Copy notes.txt to backup.txt  
```
cat notes.txt backup.txt
```

6. Show the first 100 lines of a file called logs.txt  
```
head -n 100 logs.txt
```

7. Show the last 100 lines of logs.txt  
```
tail -n 100 logs.txt
```

8. Check the disk storage usage of the server  
```
df -h
```

9. Check the running processes in the system  
```
ps -ef
```

10. Delete a file called temp.txt  
```
rm temp.txt
```


## SECTION 3 – Concept Questions

1. What is the difference between `>` and `>>` in Linux?  
`>` is override the old content and copy the given content and `>>` is used to append the content to old content.

2. What is the purpose of `kill -9` command?  
it is used to terminate the given process ID immedately

3. What is the difference between `rm` and `rmdir`?  
rm is used to delete the files and rmdir is used to delete the empty floder

4. What information does `netstat -tulpn` command provide?  
It shows running services and their port numbers in the system.

5. What is the purpose of `ping` command?  
that used to check the connectivity between system and server.


## SECTION 4 – Scenario based Questions

1. You want to check the current working directory.  
```
pwd
```

2. You want to create a directory called devops inside the home directory.  
```
mkdir devops
```

3. You want to check which process is using high CPU in the system.  
```
top
```

4. You want to check whether your server can connect to google.com.  
```
ping google.com
```

5. You want to view the last 50 lines of a log file called application.log.  
```
tail -n 50 application.log
```
