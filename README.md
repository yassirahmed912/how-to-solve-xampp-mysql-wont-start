# how-to-solve-xampp-mysql-wont-start
This is a repo to share how to solve issues with xampp wont start. 

Error: MySQL shutdown unexpectedly.
12:41:21 PM  [mysql] 	This may be due to a blocked port, missing dependencies, 
12:41:21 PM  [mysql] 	improper privileges, a crash, or a shutdown by another method.
12:41:21 PM  [mysql] 	Press the Logs button to view error logs and check
12:41:21 PM  [mysql] 	the Windows Event Viewer for more clues
12:41:21 PM  [mysql] 	If you need more help, copy and post this
12:41:21 PM  [mysql] 	entire log window on the forums

If you see such an error, here is how to solve it. 


1. you go  to c:\xampp\mysql\data.... 
2. Remove / Archive all the info files
3. Then restart Mysql Xampp server. 
