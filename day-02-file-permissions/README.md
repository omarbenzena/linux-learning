   # Day 2 — Files and Permissions
   
   ## Commands used
   
   ### ls -l used to display files and directories with detailed information
   
   ### chmod is used to change the file permissions
   
   ### rm is used to remove a file in Linux
   
   ### cp is used to copy a file in Linux
   
   ### mv is used to move a file in Linux
   
   
   ## cp vs mv vs rm
   
   cp is used to copy a file in Linux
   mv is used to move or rename a file in Linux
   rm is used to remove a file in Linux
   
   ## What r, w and x mean
   r means read permission
   w means write permission
   x means execute permission
   
   ## Before/after chmod
   Before using `chmod`, the file did not have execute permission for the owner.
   After running:
   `chmod u+x renamed.txt`
   the owner received execute permission for the file.
   
   ## Mistakes or surprises
   I made some mistakes at the beginning because I didn't know which user or group I
   was changing with `chmod`, so I wasn't sure exactly what I had changed. After
   practicing it a few times, it became much easier.
