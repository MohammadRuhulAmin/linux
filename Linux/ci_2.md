__More on ls by using directory name__   
Ans:ls [Directoryname]. Example: ls Downloads/ or ls Downloads 
Example: ls / (will show all the folders in the root directory)

__Clear terminal everything command__  
Ans: clear

__ls in a specific location__
Ans: ls /home/programmingfolder

__how to see all the list from present directory in one folder back?__  
Ans: ls ..

__how to see all the list from present directory in two folder back?__
Ans: ls ../..

__display a folder's all file in long format__
Ans: ls -l  
To see in a specific location 
    ls -l Documents/folderA/*.*

__drwxr-xr-x meaning__  
Ans: d means directory

__describe this__    
Ans:    total 184324  
    drwxr-xr-x 2 ruhul ruhul     4096 জুন       24 15:32 Desktop    
    case1 :   
        d stands for directory   
        r stands for read permission  
        w stands for write permission  
        x stands for execute  
        r stands for write  

__to see the hidden file what is the ls command ?__ 
  Ans: ls -a (hidden files are start wiht dot like .gitignore .profile .bash_history etc..)

__to see hidden files with details in a folder__
Ans :ls -al

__to see all files in a sorted order by DESC the size__  
Ans : ls -lS

__to Search all the files in a Directory like Documents ends with html extension__  
Ans : ls Documents/*.html

__to see all the documents in another way__  
Ans : ls [Folderpath]/*.*

__Suppose i want to put all the result return by the command inside a .txt file__  
Ans : ls -lS > result.txt. Here -lS will sort the file according to the file size and store the result inside .txt file.

__Display only the directories inside a directories__  
Ans : ls -d /*
ls -d /* >store.txt

__Which command will give help to know more about ls command?__  
Ans man ls