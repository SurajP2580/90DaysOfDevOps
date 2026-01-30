Task for craeting file an perform Operations.


1. touch is for creaing file ,
2. echo "Line 1" > notes1.txt-  Line 1 append (>) to text file.
3. echo "Line 2" >> notes1.txt  - Line 2 append to new line of file a end not replace
4. echo "Line 3" | tee -a notes1.txt  - LIne 3 output send to another by '|' to anoher command, 'tee' print the     output in terminal also add to txt file -a mean add at end not override.
5. head -n 2 notes1.txt- print 2 lines from beginning
6. tail -n 2 notes1.txt- print end 2 lines from file.




Output:

suraj@suraj-Aspire-A515-51G:~$ touch notes1.txt
suraj@suraj-Aspire-A515-51G:~$ echo "Line 1" > notes1.txt
suraj@suraj-Aspire-A515-51G:~$ echo "Line 2" >> notes1.txt
suraj@suraj-Aspire-A515-51G:~$ echo "Line 3" | tee -a notes1.txt
Line 3
suraj@suraj-Aspire-A515-51G:~$ cat notes1.txt
Line 1
Line 2
Line 3
suraj@suraj-Aspire-A515-51G:~$ head -n 2 notes1.txt
Line 1
Line 2
suraj@suraj-Aspire-A515-51G:~$ tail -n 2 notes1.txt
Line 2
Line 3
