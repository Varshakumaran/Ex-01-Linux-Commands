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

<img width="1041" height="185" alt="image" src="https://github.com/user-attachments/assets/1f5065d9-4269-4b55-b192-84d303b26bea" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="575" height="106" alt="image" src="https://github.com/user-attachments/assets/fb0b4085-4678-406d-831d-59e3e37abdc8" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="737" height="224" alt="image" src="https://github.com/user-attachments/assets/63aa6eef-ba61-4247-9d43-badc56aa3fee" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="1030" height="183" alt="image" src="https://github.com/user-attachments/assets/af53277b-6c50-48c1-8f6a-13e39b335214" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="501" height="156" alt="image" src="https://github.com/user-attachments/assets/841fc823-25d9-4857-8918-255142df201e" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="513" height="241" alt="image" src="https://github.com/user-attachments/assets/daa4085c-2182-4f05-a083-f3e7c98690df" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="523" height="187" alt="image" src="https://github.com/user-attachments/assets/9faf9e72-11b4-4a9e-b74c-0bd1fa89e25f" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="1060" height="387" alt="image" src="https://github.com/user-attachments/assets/c7f01fac-b086-4394-b6ff-5a4193f3b1cd" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="485" height="148" alt="image" src="https://github.com/user-attachments/assets/f87127a1-4772-4b9e-807b-bc30c21643bd" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="593" height="375" alt="image" src="https://github.com/user-attachments/assets/5ba06aa8-f9ed-42d2-b747-69d360a0c5d0" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="529" height="186" alt="image" src="https://github.com/user-attachments/assets/d7130d5f-da75-4e44-b89d-ad328e7b4571" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="403" height="549" alt="image" src="https://github.com/user-attachments/assets/90fc20e3-5d6e-4c1b-bb17-9d7397cbbd77" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="385" height="382" alt="image" src="https://github.com/user-attachments/assets/bc9a8383-0cbe-4e82-9c86-1d9dde773250" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1041" height="107" alt="image" src="https://github.com/user-attachments/assets/4bec8bf5-2315-4a07-bb68-35f221fe0c01" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="560" height="347" alt="image" src="https://github.com/user-attachments/assets/1e441922-e6b7-4aa1-9d14-ea9365b6e33e" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="593" height="554" alt="image" src="https://github.com/user-attachments/assets/96ad6e9f-f509-440e-ab99-890059902782" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="389" height="70" alt="image" src="https://github.com/user-attachments/assets/230e7a63-7128-4634-9ffb-1995fe468cfd" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="1061" height="461" alt="image" src="https://github.com/user-attachments/assets/6d8c927c-efa0-4e79-8572-abbda41aedd6" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="974" height="219" alt="image" src="https://github.com/user-attachments/assets/aff6af3f-7a4e-460d-8f60-4e8d6f461e5f" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="1058" height="613" alt="Screenshot 2025-09-15 101701" src="https://github.com/user-attachments/assets/32d2a80a-eeab-46cb-9773-cf194504b858" />

<img width="1010" height="360" alt="image" src="https://github.com/user-attachments/assets/cc4c0e36-6190-4ce1-a162-c520f21ebafe" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="1000" height="559" alt="image" src="https://github.com/user-attachments/assets/22bfeda7-5a28-462e-8a92-1d7b5f6bc9df" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="1046" height="367" alt="image" src="https://github.com/user-attachments/assets/e121bdbb-3b16-41a8-bfae-e049862e1512" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="840" height="208" alt="image" src="https://github.com/user-attachments/assets/477521f6-2003-4de2-8710-b82e447eaac9" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="1031" height="183" alt="image" src="https://github.com/user-attachments/assets/36bbe985-dec8-4fc8-8b89-a631f830f276" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="367" height="543" alt="image" src="https://github.com/user-attachments/assets/94fbdaf3-4207-4d2c-b370-99d0891bff19" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="224" height="191" alt="image" src="https://github.com/user-attachments/assets/9cf4d551-f147-48c0-8d23-5428b2a7d082" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="329" height="80" alt="image" src="https://github.com/user-attachments/assets/d327f49b-9490-4f0c-9119-164aad3c0d65" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="301" height="74" alt="image" src="https://github.com/user-attachments/assets/99a529c9-3c5d-4719-b70b-0fa75849b74a" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="1021" height="305" alt="image" src="https://github.com/user-attachments/assets/e5657838-1d76-4874-b5ed-2a03482e7890" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="1033" height="230" alt="image" src="https://github.com/user-attachments/assets/253979c0-9e6a-4451-a97f-7fecd10ce107" />




## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
