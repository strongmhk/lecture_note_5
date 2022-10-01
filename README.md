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






