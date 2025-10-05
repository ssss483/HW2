# I/O Redirection

### output  
**1. standard output:** screen
**2. (command) > (file):** create, save the output in a file
**3. cat (file):** displays content of a text file
**4. (command) >> (file):** appand the output in a file  
  + append means just add (not change file's data)

### input
**1. standard input:** keyboard
**2. (command) < (file):** file will be input of the command
  + sort < (file1) > (file2): sorting the file1 and save the data in the file2

# others
**1. Pipeline:** |, output of previous command to input of next command( information flows in one way)
  + wc : word count

**2. Expansion:** special characters expand its meaning when given to shell commands. 
  + echo (text): echo print text next to the command echo
  + echo *: print every content in current file
  + echo ~: user's current home directory's addrass
  + (back slash): in long command for readability, back slash menas ignore line change in command enter 


**3. Permission:** Linux is multy-user system so there is a need to share authority.( read, write, excute )
  + |- or d | owner's authority | group's authority | other's authority |  
  |-:file, d:directory | rwx|rwx|rwx|
  + *chmod: changing permission*
    |chmode |n1|n2|n3| (file)|  
    |   |owner's authority|group's authority | other's authority |
  +7: rwx
  +6: rw-
  +5: r-x
  +4: r--
  +0: ---

**4. Superuser:**
  +sudo (command):** excute the commend in superuser's authority
  +sudo -i:** run with superuser privileges for a while, and tern usermode to type exit

**5. text editor:**
  + vi, vim
  + Emacs
  + nano
  + gedit
  + kwrite
**6. history:** see previous command history
    
**7. download**
  + wget (URL): download files from the internet directly to your directory
  + curl (options) (URL): download and uploading data over the internet
**7. grep**
  + grep (search_term) file
    
# Shell Script
**1. nano (script file):**


  

      
