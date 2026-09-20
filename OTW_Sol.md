LAB 6 --> 7 :
Q)The password for the next level is stored somewhere on the server and has all of the 
following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

SOl: find / -user bandit7 -group bandit6 -size 33c
___________________________________________________________________________________________

LAB 7 --> 8
Q)The password for the next level is stored in the file data.txt next to the word millionth

SOl: cat data.txt | grep -i "millionth"
____________________________________________________________________________________________

LAB 8 --> 9
Q)The password for the next level is stored in the file data.txt and is the 
only line of text that occurs only once

SOL: cat data.txt | sort | uniq -u

___________________________________________________________________________________________

LAB 9 --> 10
Q)The password for the next level is stored in the file data.txt in one of the few 
human-readable strings, preceded by several ‘=’ characters.

SOl:  strings data.txt | grep "=="

___________________________________________________________________________________________

LAB 10 --> 11
Q)The password for the next level is stored in the file data.txt, which contains base64 
encoded data

SOl:

___________________________________________________________________________________________

LAB 11 --> 12
Q)The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters h
ave been rotated by 13 positions

SOl:

___________________________________________________________________________________________

LAB 12 --> 13
Q)The password for the next level is stored in the file data.txt, 
which is a hexdump of a file that has been repeatedly compressed. 
For this level it may be useful to create a directory under /tmp in which you can work. 
Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. 
Then copy the datafile using cp, and rename it using mv (read the manpages!)

SOl:
