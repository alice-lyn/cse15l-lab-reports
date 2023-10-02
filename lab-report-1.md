# Lab Report 1
## cd 
1. no argument:
   ```
   [user@sahara ~]$ cd 
   [user@sahara ~/lecture1]$ pwd
   /home
   ```
   * the working directory is /home
   * the directory was set to /home after running the code
     No argument means resetting whatever the working directory is to /home
   * the output is not an error
     
2. to a directory:
   ```
   [user@sahara ~]$ cd lecture1
   [user@sahara ~/lecture1]$ pwd
   /home/lecture1
   ```
   * the working directory is /lecture1 
   * the directory was changed to /lecture1 under /home 
   * the output is not an error
     
3. to a file:
   ```
   [user@sahara ~/lecture1]$ cd Hello.class
   bash: cd: Hello.class: Not a directory
   [user@sahara ~/lecture1]$ pwd
   /home/lecture1
   ```
   * the working directory is still /lecture1, the directory containing the file I attempted to open
   * i got the output because a file is not a directory
   * the output is an error because a file is not a directory 


## ls 
1. no argument:
   ```
   [user@sahara ~/lecture1]$ ls
   Hello.class  Hello.java  messages  README
   [user@sahara ~/lecture1]$ pwd
   /home/lecture1
   ```
   * the working directory is /lecture1
   * i got the output because by running ls with no arguments, it returns all the files and folders in the current directory
   * the output is not an error
     
2. to a directory:
   ```
   [user@sahara ~/lecture1]$ ls messages
   en-us.txt  es-mx.txt  ko.txt  zh-cn.txt
   [user@sahara ~/lecture1]$ pwd
   /home/lecture1
   ```
   * the working directory is /lecture1
   * i got the output because by running ls with a path to a directory, it returns all the files and folders in that specific directory; however, the directory wasn't changed
   * the output is not an error
     
3. to a file:
   ```
   [user@sahara ~/lecture1]$ ls Hello.class
   Hello.class
   [user@sahara ~/lecture1]$ pwd
   /home/lecture1
   ```
   * the working directory is /lecture1
   * by running ls with a path to a file, it returns the name of the file because there is only one file in that file (not sure if i explain this right)
   * the output is not an error 

## cat 
1. no argument:
   * 
2. to a directory:
   * 
3. to a file:
   * 
