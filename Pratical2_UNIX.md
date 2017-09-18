# Practical2_UNIX
Katherine Tansey  
8/8/2017  

# Learning Objectives

Understand UNIX command syntax       
Learn basic UNIX commands              

# Last Time
/ on its own is the root directory of the whole file system        
A relative path specifies a location starting from the current location          
A full (absolute) path specifies a location from the root of the file system          
.. means ‘the directory above the current one’        
Up-arrow to scroll up through previous commands to edit and repeat them      

**There is no trash bin: once something is deleted, it is gone**    

# Command line syntax
![](pictures/syntax.png)    


* **Command** name tells the computer the operation/program/job to perform.
    * ALWAYS a single word
* A command can take **options**
    * Although not always, they are optional 
    * Usually preceded by a dash
    * Change the behaviour of the command: usually the style in which the output is given.
* **Arguments** gives the computer the required input
    * Usually file or directory names
    * Not always required
    
### Practical
Move to your Documents folder on your computer. This will be slightly different for everyone depending on which operating system you are using. Use cd and pwd to move and check where you are, and use ls to see what each directory contains.       

# ls
List directory contents.

Useful options:

* -a  $\rightarrow$ all
* -l  $\rightarrow$ long format
* -t  $\rightarrow$ sort by time modification
* -h  $\rightarrow$ print files sizes in human readable format
* -F  $\rightarrow$ add a trailing / to directories


