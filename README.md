# lecture_note_5


### Standard Output 
---
- > : Create and save the output in a file
***ex)*** $ ls -lh > file_list.txt    
            
          
- >> : Appends output ti an existing file (if it already exist) 
***ex)*** $ ls -lh >> file_list.txt  

- cat : Displays the content of text file  
***ex)*** $ cat file_list.txt  
---

### Standard Output
---
- < : Redirect input from a file (can mix '<' and '>') 
***ex)*** $ sort < words.txt > sorted_words.txt  
           
- |(piplines) : Feeds output of previous command to input of next command  
***ex)*** $ ls -lh | less  
$ ls | wc -l

- echo : Speacial characters expand its meaning when given to shell commands  
***ex)*** $ echo print out the text  
$ echo *  
$ echo ~  

---  

Back slash : used to ingnore line change in command  
***ex)*** $ ls -l \  
--reverse \  
--human-readable \  

### Permissions   
-rwdr-xr-x  -> 111 101 101  
owner / group / others  

-chmod : change permission  
***ex)*** chmod 600 some_file  
rwx = 111 in binary = 7  
rwx = 110 in binary = 6  
rwx = 101 in binary = 5  
rwx = 100 in binary = 4  

### Superuser  
*Superuser has all system administration authority*  
***ex)*** $ sudo some_command  
***ex)*** sudo -i  <- all authority  
Type 'exit' <- get out of a superuser session  

### Text Editors  
- vi, vim  
- Emacs  
- nano  
- gedit  
- kwrite  

### Shell Script  
Write and run a shell script  

***ex)*** $ nano myscript.sh  

### History  
history : see previous command history  

***ex)***  
$ history > history_command.txt  
$ cat history  













