# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="1041" height="185" alt="Screenshot 2025-09-15 101114" src="https://github.com/user-attachments/assets/467d90df-6947-47ca-a8d7-7771e22e3b6c" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="575" height="106" alt="Screenshot 2025-09-15 101129" src="https://github.com/user-attachments/assets/842b32c8-a99f-4f9f-a068-c8444b922072" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="737" height="224" alt="Screenshot 2025-09-15 101142" src="https://github.com/user-attachments/assets/bb4a3adc-ebf4-424a-aaa4-6f4211f044cd" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="1030" height="183" alt="Screenshot 2025-09-15 101153" src="https://github.com/user-attachments/assets/2522c94a-c0a4-4f52-824c-cce5242cc1f6" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="501" height="156" alt="Screenshot 2025-09-15 101214" src="https://github.com/user-attachments/assets/9e54161e-e89c-4c41-b88c-4527407752f2" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="513" height="241" alt="Screenshot 2025-09-15 101230" src="https://github.com/user-attachments/assets/27a48e4b-0e5f-4601-b562-3409ad58519f" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="523" height="187" alt="Screenshot 2025-09-15 101241" src="https://github.com/user-attachments/assets/24106f91-b456-482e-9d0a-4fd00c0e6a7d" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="1060" height="387" alt="Screenshot 2025-09-15 101259" src="https://github.com/user-attachments/assets/e2283183-f746-444b-ad2e-2e9a1fdda546" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="490" height="151" alt="image" src="https://github.com/user-attachments/assets/5503c7c9-d4c0-4b48-be22-e17affc7d0a5" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="608" height="379" alt="image" src="https://github.com/user-attachments/assets/b65520d9-69a7-4bf4-9bd1-0d79a1073f8f" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="533" height="198" alt="image" src="https://github.com/user-attachments/assets/57299335-e27c-4bba-87dc-92028367d229" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="358" height="551" alt="image" src="https://github.com/user-attachments/assets/858cb0bb-d55f-4ae3-b803-c4134706c798" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="363" height="371" alt="image" src="https://github.com/user-attachments/assets/c24549e4-556a-4020-ab3a-91831e0899a9" />


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1041" height="107" alt="Screenshot 2025-09-15 101420" src="https://github.com/user-attachments/assets/50284af5-af60-4209-9259-15b4823548a5" />



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="560" height="347" alt="Screenshot 2025-09-15 101434" src="https://github.com/user-attachments/assets/8ca4b8bd-33c5-4edb-8986-4bd83b96cd58" />



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="593" height="554" alt="Screenshot 2025-09-15 101451" src="https://github.com/user-attachments/assets/0bf8345f-47a4-4c17-83ff-f92d8f8dd95f" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="389" height="70" alt="Screenshot 2025-09-15 101507" src="https://github.com/user-attachments/assets/26219e19-a65c-4a13-a47c-7d5d783788fb" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c



<img width="1061" height="461" alt="Screenshot 2025-09-15 101518" src="https://github.com/user-attachments/assets/e84af15c-93ee-4a6e-9238-5410cc4f152e" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


<img width="974" height="219" alt="Screenshot 2025-09-15 101531" src="https://github.com/user-attachments/assets/0bcf72d0-9d20-4dbe-8b02-cceaa2e5c32c" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


<img width="1058" height="613" alt="Screenshot 2025-09-15 101701" src="https://github.com/user-attachments/assets/4776384b-c535-4ea5-bea3-4f84904a0505" />



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="1010" height="360" alt="Screenshot 2025-09-15 101706" src="https://github.com/user-attachments/assets/8e4dedc6-d1fd-440b-977e-2a2bd348c48e" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


<img width="1000" height="559" alt="Screenshot 2025-09-15 101740" src="https://github.com/user-attachments/assets/2875e0a4-06b2-4334-b5cd-89d984fa8824" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


<img width="1046" height="367" alt="Screenshot 2025-09-15 101800" src="https://github.com/user-attachments/assets/b61aa868-0b04-49af-9ca8-29dad78a7647" />



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


<img width="840" height="208" alt="Screenshot 2025-09-15 101812" src="https://github.com/user-attachments/assets/f43fc4f8-db99-4a2a-8a9d-35813ddcc459" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


<img width="1031" height="183" alt="Screenshot 2025-09-15 101824" src="https://github.com/user-attachments/assets/9e6b3c14-9482-43f8-8dbc-b34e4cd06fee" />


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


<img width="367" height="543" alt="Screenshot 2025-09-15 101836" src="https://github.com/user-attachments/assets/c35d0d8b-fcbd-4822-a10c-466d7661f597" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="224" height="191" alt="Screenshot 2025-09-15 101846" src="https://github.com/user-attachments/assets/7275c159-f3d9-41d4-9133-a064b8faf752" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


<img width="329" height="80" alt="Screenshot 2025-09-15 101856" src="https://github.com/user-attachments/assets/e91ba700-1aad-4938-9bd9-c3ad7a339934" />


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


<img width="1038" height="300" alt="image" src="https://github.com/user-attachments/assets/a18dea76-ea39-4526-951c-6f45f741f967" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


<img width="1045" height="230" alt="image" src="https://github.com/user-attachments/assets/9a9f251d-1ace-4132-88da-bacb2bdfb600" />



## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
